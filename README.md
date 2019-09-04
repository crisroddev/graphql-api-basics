# graphql-api-basics
## Mongo Relations
- BD:
```
createdEvents: [
        {
            type: Schema.Types.ObjectId,
            ref: 'Event'
        }
    ]
```
-  ref: 'Event, cause event model y called Event 
```
module.exports = mongoose.model('Event', eventSchema);
``` 
- args
```
createUser(userInput: UserInput): User
```
- args will be userInput
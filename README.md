# Angular-Chat
Emoji suggestions in an Angular application using sentiment analysis

## Prerequisites
- [Angular](https://angular.io)
- [Express](https://expressjs.com/)
- [Pusher](https://pusher.com)
- [Sentiment](https://github.com/thisandagain/sentiment)
- A [Pusher account](https://pusher.com/signup) and [Pusher app credentials](http://dashboard.pusher.com/)


## Getting started
- Clone the project and install dependencies:
- Create a file named `.env`. Update the `.env` file with the content below:

```
PUSHER_APP_ID=your-app-id
PUSHER_APP_KEY=your-app-key
PUSHER_APP_SECRET=your-app-secret
```

- Update the `pusher.service.ts` file with your pusher key

> **Note**: ensure to replace the placeholder values with your pusher `appId`, `key` and `secret`.


```
git clone https://github.com/christiannwamba/angular-chat.git
cd angular-chat && npm install && npm start
```

## Built With

* [Pusher](https://pusher.com/) 
* [Angular](http://angular.io)  

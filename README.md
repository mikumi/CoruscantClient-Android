# CoruscantClient-Android

We want to build a simple client app that looks up a person via an API and displays the fetched name, age and job on the client.

#### API

- *URL to look up a person:* `https://coruscant-one.firebaseio.com/people/{name}.json`
- *Query Parameter:* `"auth" : {auth_token}`
- *Return:* A person with format:
```{ 
 “name” : “A name”,
 “job” : “A job”,
 “age” : 100
}```

#### Create an UI

The UI should be very simple:

- A way to enter the name of the person that we want to look up (e.g. via a text field)
- A submit button to submit the request
- Anything to display the fetched name, age and job

#### Use this information for testing

- *Auth token:* `7Ym0TKci1i5otNZORBrDQJiz6Wmd8T0jBbpSVO48`
- *Person to look up:* `yoda`

#### Notes

- You can either fetch this repository (empty project) or create a project from scratch
- You can use anyting that you would use in your normal job as well (Google, Stackoverflow ...)

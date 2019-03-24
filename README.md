# Firebase Firestore and Angular ToDo List App

Navigate to your environment.ts file and update your firebaseConfig. It is now necessary to have a projectId when initializing firebase, so make sure it’s included in the config object.

```Javascript
export const environment = {
    production: true,
    firebaseConfig: {
       apiKey: "",
       authDomain: "",
       databaseURL: "",
       projectId: "",
       storageBucket: "",
       messagingSenderId: ""
     }
};
```

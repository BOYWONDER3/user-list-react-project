## In this simple Project i completed the following thereby testing my knowledge in fetching an API using the useEffect and redring of props using keys

1. Fetched all users from the API (https://jsonplaceholder.typicode.com/users) in my App.jsx file using useEffect.
2. Rendered an h1 that says User List and below that a ul containing a list of all users. This is a perfect use case for fragments since i don't want to wrap it in an extra div.
3. The users in the list contained their own component and that component contained a name prop and returned the name inside an li elemen
4. Added a loading state that displays the text Loading... instead of the user list while it is being downloaded from the API
7. I used my dev tools to throttle my network speed to more easily test the loading. Go to the Network tab, click the No Throttling drop down and choose Slow 3G.

# weDevs-que-1

```
let allRead = true;

let notifications = [
  {message: ‘Lorem’, read: true},
  {message: ‘Ipsum’, read: true},
  {message: ‘Dolor’, read: true},
  {message: ‘Sit’, read: false},
  {message: ‘Amet’, read: true}
];

notifications = notifications.map(item => ({ ...item, read: allRead }));

console.log(notifications);
```

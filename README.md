# Author
![@suhitk1](https://avatars1.githubusercontent.com/u/20357099?v=3&u=4c1555ae5490d2155959e65c2dd930e782f1c703&s=400)

Created by suhitk1

[Github](https://github.com/suhitk1) | [FreeCodeCamp](http://www.freecodecamp.com/suhitk1) | [CodePen](http://codepen.io/suhitk1/) | [E-Mail](mailto:suhit.kmr1@gmail.com)

# FreeCodeCamp API: File Metadata Microservice
## User stories:
1. I can submit a FormData object that includes a file upload.
2. When I submit something, I will receive the file size in bytes within the JSON response

**Hint:** You may want to use this package: https://www.npmjs.com/package/multer

## Example query usage:

Upload file from the UI at the root.
```text
https://file-metadata-r282.herokuapp.com
```

## Example query output:

```text
https://file-metadata-r282.herokuapp.com/upload
```

```js
{
"name": "2016-01-26.png",
"size": 258957,
"date": "1/27/2016, 1:30:52 AM",
"file": "1453858252196.png"
}
```

The information displayed is all the information that is stored in a database. The files then gets deleted rigth away.
In the future, uploading the the cloud could be implemented and then with the database the files could be retrieved using a get, this si not yet implemented and not in any futures plans to be.

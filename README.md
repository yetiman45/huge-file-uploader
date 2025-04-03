# Huge File Uploader

A Node.js module to upload large files efficiently.

## Installation

```bash
npm install huge-file-uploader
```

## Usage

```javascript
const { Uploader } = require('huge-file-uploader');

const uploader = new Uploader('myUploads'); // Set upload directory

uploader.uploadFile('path/to/largefile.mp4')
    .then((filePath) => console.log(`File uploaded to: ${filePath}`))
    .catch((err) => console.error(`Upload failed: ${err.message}`));
```

## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/license/mit) file for details.

## Contributing

Feel free to open an issue or submit a pull request if you'd like to contribute to this project.

## Author

Dipin Niroula - dipinniroula@hotmail.com, dipin@roqos.com  
www.roqos.com


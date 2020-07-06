# StarUML Watermarker Remover

Remove StarUML "UNREGISTERED" watermark from `svg` exported files

## 📦 Installation

Clone this repository
```bash
git clone https://github.com/nikhilracha/staruml-watermark-remover.git
```

## 🚿  Usage

Execute package for help
```bash
java -jar target/staruml-watermark.jar
```

Remove watermarks for a directory

Go into the directory and then use this command
```bash
java -jar target/staruml-watermark.jar -d /path/to/project
```

Remove watermarks for a directory recursively
```bash
java -jar target/staruml-watermark.jar -r -d /path/to/project
```


## 🎓 License
This project is licensed under the [MIT](LICENSE) License.

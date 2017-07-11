# dl_multithreading

HTTP大文件多线程下载工具，支持断点续传

## 使用说明

```
Usage: dl_multithreading.py list_file [save_dir]
Options:
    list_file  下载列表文件，一行一个。
    save_dir   保存目录，可选参数，默认为当前文件夹。
Example:
    dl_multithreading.py list.txt ./download
```
---
sidebar_position: 1
---

# Tutorial Intro

Let's discover **Docusaurus in less than 5 minutes**.

## General Introduction of curl

**[cURL](https://curl.se/docs/)** is a command-line tool that you can use to transfer data via network protocols. The name cURL stands for **Client URL**, and is also written as **curl**. This popular command uses URL syntax to transfer data to and from servers. Curl is powered by [libcurl](https://curl.se/libcurl/), a free and easy-to-use client-side URL transfer library that supports a range of protocols. The most common protocols supported and, that are mainly used are HTTP and FTP.
Curl is generally used this way:

```shell
curl [option][url]
```
If you do not specify a protocol, curl uses HTTP by default.

## Explanation of the GET curl Command

The GET curl command is the simplest and most common operation that is made using HTTP is to GET a URL. This is simply trying to retrieve a resource from the URL. The URL could be anything from a web page, an image, or any file. The client sends a GET request to the server and receives the document it asked for. If you run this in your terminal:

```shell
curl https://www.google.com
```
you will get a [Google](https://www.google.com) page returned in your terminal window.

## How to Download an Image with curl

To download and save an image or any file using curl, there are two `options` that you need to know about: **o** and **O**(small and the capital letter O respectively). The difference is that the small letter **o** allows you to give your preferred name to the file you intend to download, while capital letter **O**  downloads and saves the image as it is from the resource.

Look at the following command:

```shell
curl -o myimagename.png https://documentwrite.dev/wp-content/uploads/2021/08/document-write-logo.png
```


```shell
curl -O https://documentwrite.dev/wp-content/uploads/2021/08/document-write-logo.png
```

Running the first command in your terminal will download the image with its as ***myimagename.png***. The second command will download with its name as ***document-write-logo.png*** which is the original file's name.

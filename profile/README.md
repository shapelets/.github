<p align="center">
<img src="https://github.com/shapelets/.github/blob/main/profile/logo.png" width="400">
 
[Docs](https://shapelets.io/doc/contents.html) | [Releases](https://shapelets.io/doc/release_notes/index.html) | [Examples](https://shapelets.io/ebooks-webinars/) | [Resources](https://shapelets.io/resources/)
 
# Making the most of your data processing platform
 
Shapelets is a data science and time series ecosystem for data scientists, and business analysts to bring your ideas to life, and a great opportunity for data engineers and architects to deliver rapid solutions across their organization.
</p>
 
![shapelets structure](https://github.com/shapelets/.github/blob/main/profile/architecture.png)
 
## Why is Shapelets special?
 
1. Much faster performance with much less resources.
 
2. Accelerated development of time series analytics.
 
3. Unlimited users and pay-per-use.
 
## Getting Started
 
Develop accelerated solutions that integrate seamlessly with your data ecosystem.
 
### Install
 
To install a binary distribution, the only requirement is to have a working (recent, 3.7.3 and onwards) version of Python in your system. If you don’t have Python yet, you can download it here.
 
#### PIP
 
To install Shapelets using pip, you can install them with:
 
>>> pip install shapelets-platform
 
> **_NOTE:_**  Using a virtual environment or Docker is a good idea to avoid conflicts between libraries installed on your system. If you are not familiar with these methods, you can find the instructions below.
 
If you want to use the Virtual File System (VFS) feature, you need to install the drivers. You can do it with:
 
>>> pip install shapelets-platform[vfs-all]
 
Alert: With all options, you will install all the drivers. We currently support Azure Blob Storage Gen1 & Gen2, Server Message Block (SMB) and the local filesystem. Other fsspec-compatible protocols will be available soon.
 
To check if Shapelets is installed, you can execute the following:
 
>>> python -c "import shapelets as sh; print(sh.__version__)"
 
It’s a good idea to use a virtual environment or docker image, to avoid conflicts between versions.
 
#### Conda
 
Currently, conda installation is not available.
 
## Helpful links
 
-   [Documentation](https://shapelets.io/doc/contents.html)
-   [Releases](https://shapelets.io/doc/release_notes/index.html)
-   [Use Cases](https://shapelets.io/ebooks-webinars/)

# ShareFile
这个项目实现Android 进程间文件分享，ShareFileClient和ShareFileServer为两个应用程序。ShareFileServer实现ContentProvider，为ShareFileClient提供分享文件。ShareFileClient通过StartActivityForResult传递Intent向
ShareFileServer发送请求文件信息。ShareFileServer将共享的文件显示在列表中，供客户端选择，待客户端选好文件之后，ShareFileServer返回该文件的Uri给客户端。ShareFileServer文件来源与手机内存，即文件夹/data/data/包名下的文件
  项目详细介绍查看我的博客：http://blog.csdn.net/lin962792501/article/details/52164695

 

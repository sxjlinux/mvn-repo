# mvn-repo
只需要在pom.xml加入以下信息即可使用maven来自动下载依赖jar   
\<repositories\>  
  \<repository\>  
    \<id\>mvn-repo\</id\>  
    \<url\>https://raw.github.com/sxjlinux/mvn-repo/master\</url\>  
    \<snapshots\>  
      \<enabled>true\</enabled\>  
        \<updatePolicy\>always\</updatePolicy\>  
     \</snapshots\>  
  \</repository\>  
\</repositories\>  
  
\<dependencies\>  
    \<dependency\>  
      \<groupId\>com.wincom.publicmodel\</groupId\>  
        \<artifactId\>path\</artifactId\>  
        \<version\>2.0\</version\>  
    \</dependency\>  
\</dependencies\>  


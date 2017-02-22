#  1.使用请先添加gradle依赖:
   
      (1) 根目录gradle加入：
      
          allprojects {
		       repositories {
		         	...
	         		maven { url "https://jitpack.io" }
        		}
        	}     
                  
      (2) 自己app gradle加入：
      
          compile 'com.github.yeyuqingchen:yechat:-SNAPSHOT'
       

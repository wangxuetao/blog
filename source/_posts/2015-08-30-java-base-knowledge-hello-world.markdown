---
layout: post
title: "hello world 程序"
date: 2015-08-30 22:22:14 +0800
comments: true
categories: java-base
---



- 汇演看世界 你会有不同的选择
- 和你一起去看流星雨客户？
- 还是不去了吧


<pre>
<code>
    InputStream input = … ; // get the InputStream from the client socket  
    BufferedReader reader = new BufferedReader(new InputStreamReader(input));  
      
    String nameLine   = reader.readLine();  
    String ageLine    = reader.readLine();  
    String emailLine  = reader.readLine();  
    String phoneLine  = reader.readLine();  
</code></pre>
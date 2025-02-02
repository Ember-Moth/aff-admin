  新增api地址：https://github.com/gunzi-666/affapi   



  使用方法

  先在面板后端 添加上面的api地址中的文件

  然后 部署一个新的站点   把dist传上去    修改config.js（里面每一项都有注释）

  伪静态写
  ```
location / {
  try_files $uri $uri/ /index.html;
}
  ```

祝你们用的愉快！！！

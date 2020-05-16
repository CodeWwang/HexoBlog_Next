---
title: 关于我
type: 'about'
---

---

JAVA后端，相当Five的IT民工。记录一下生活，分享记录学习路上的问题和经验。

目前从事信息安全这个方向，平时下班偶尔上传点东西，笔记和自己总结的知识点，欢迎交流！

我的QQ：592245268

后面会不断提升博客的质量和上传代码的质量，不断产出原创内容，持续迭代。

家里有个可爱漂亮厨艺高超的宝宝真好，冲冲冲！

```java
 @Override
    protected void doGet(HttpServletRequest req, HttpServletResponse resp) throws ServletException, IOException {
        ServletContext servletContext = this.getServletContext();
        String username = (String) servletContext.getAttribute("username");
        resp.setContentType("text/html");
        resp.setCharacterEncoding("UTF-8");
        resp.getWriter().write(username+",I lOVE U");
    }
    @Override
    protected void doPost(HttpServletRequest req, HttpServletResponse resp) throws ServletException, IOException {
        doGet(req, resp);
    }
```


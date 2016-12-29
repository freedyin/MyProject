# MyProject
test the git
 String url = "http://hq.sinajs.cn/list=sz002029";
 URL u = new URL(url);
 InputStreamReader isr=new InputStreamReader(u.openStream(),"gbk");
 BufferedReader br=new BufferedReader(isr);


1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:
<script type="text/javascript">
        	var s1 = new String('你好');
        	var s2 = new String('王小明');
        	var s3 = s1.concat(s2);
        	document.getElementById('h1').innerHTML=s3;       

        	
</script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:
<script type="text/javascript">
	    var str = '87';
       
        var estr = str.padEnd(6,0);
        document.getElementById('h2').innerHTML=estr;      
</script>
3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:
<script type="text/javascript">
			
			var num = new Number(79387.348);
			var num2 =num.toFixed(2);
            document.getElementById('h3').innerHTML=num2;       
</script>
4.一张图片是一个相对路径img/head/,icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:
<script type="text/javascript">
			  var str = 'img/head/icon/1.jpg';
        
              var nstr = str.slice(0,14);
       
              document.getElementById('h4').innerHTML=nstr; 
</script>
5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答:

  
   <script>
        var yzm = prompt('请输入验证码');
        document.getElementById('h4').innerHTML=yzm.toLocaleUpperCase();; 
        </script>

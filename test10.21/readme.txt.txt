1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:
    	<script type="text/javascript">
			var h1 = document.getElementById("h1");
			var str1="字符串1";
			var str2="字符串2";
			var d = str1.concat(str2);
            console.log(d);
		</script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:
       
       <script>
		    var money=parseInt(prompt("存储金额为："));
			var h2=document.getElementById("h2");
			h2.innerHTML="您的存储金额为："+money;
	    </script>

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:
      
      	<h3 id="h3"></h3>
		<script>
			var num=79387.348;
			var h3=document.getElementById("h3");
			h3.innerHTML=num.toFixed(2);
		</script>

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:
        	<body>
		<img src="img/head/icon/1.jpg" id="img"/>
		<h4 id="h4"></h4>
		<script type="text/javascript">
			var img=document.getElementById("img");
			var h4=document.getElementById("h4");
			h4.innerHTML=img.src;
	    </script>
	</body>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h1的元素中,显示在页面id为h4的元素中
答:

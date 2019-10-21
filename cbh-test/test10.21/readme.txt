1.将两个字符利用字符串对象的方法变成一个字符,显示在页面id为h1的元素中
答:

<div id="h1"></div>
    <script>
        var a='123'
        var b='456'
        var c=a.concat(b);
        // console.log(c);
        var d=document.getElementById('h1').innerHTML=c;
    </script>

2.一个富豪想存87万,给理财顾问写了87w,请自动生成存储870000的方法,显示在页面id为h2的元素中
答:

<div id="h2"></div>
    <script>
        var a=87
        var b=a.padStart(6,0);
        var c=document.getElementById('h2').innerHTML=b;
    </script>

3.一个数字79387.348的工程款,保留两位小数存入,显示在页面id为h3的元素中
答:

<div id="h3"></div>
    <script>
        var a=79387.348;
        var b=a.toFixed(2);
        var b=document.getElementById('h3').innerHTML=b;
    </script>

4.一张图片是一个相对路径img/head/icon/1.jpg,我只需要拿到它的文件夹目录后显示在页面id为h4的元素中
答:

<div id="h4"></div>
    <script>
        
    </script>

5.用户输入验证码,无论大小写输入都会正确的方法,显示在页面id为h5的元素中
答:

<input type="text" id="h5">
    <button id="btn">点击</button>
    <script>
        btn.onclick.function(){
            var a=document.getElementById('h5').value;
            if(a == ){
                alert('输入正确')
            }
        }
        
    </script>

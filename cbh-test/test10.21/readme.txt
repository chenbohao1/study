1.�������ַ������ַ�������ķ������һ���ַ�,��ʾ��ҳ��idΪh1��Ԫ����
��:

<div id="h1"></div>
    <script>
        var a='123'
        var b='456'
        var c=a.concat(b);
        // console.log(c);
        var d=document.getElementById('h1').innerHTML=c;
    </script>

2.һ���������87��,����ƹ���д��87w,���Զ����ɴ洢870000�ķ���,��ʾ��ҳ��idΪh2��Ԫ����
��:

<div id="h2"></div>
    <script>
        var a=87
        var b=a.padStart(6,0);
        var c=document.getElementById('h2').innerHTML=b;
    </script>

3.һ������79387.348�Ĺ��̿�,������λС������,��ʾ��ҳ��idΪh3��Ԫ����
��:

<div id="h3"></div>
    <script>
        var a=79387.348;
        var b=a.toFixed(2);
        var b=document.getElementById('h3').innerHTML=b;
    </script>

4.һ��ͼƬ��һ�����·��img/head/icon/1.jpg,��ֻ��Ҫ�õ������ļ���Ŀ¼����ʾ��ҳ��idΪh4��Ԫ����
��:

<div id="h4"></div>
    <script>
        
    </script>

5.�û�������֤��,���۴�Сд���붼����ȷ�ķ���,��ʾ��ҳ��idΪh5��Ԫ����
��:

<input type="text" id="h5">
    <button id="btn">���</button>
    <script>
        btn.onclick.function(){
            var a=document.getElementById('h5').value;
            if(a == ){
                alert('������ȷ')
            }
        }
        
    </script>

# QS_EXT_ShowHTMLfromMeasure
<br>
Qlik Sense Extension
<br>
<img src="https://i.ibb.co/18cx8T9/showHTML.png" alt="showHTML" border="0" />


<br>
<b>Sample measure code:</b><br>

```ruby
='<b>Bold Measure: '&sum(100000) * 5 &'</b>'
&'<br>Line 2 with num(measure) :'&Num(sum(88888.555),'###,###.#')
&'<br>Line 3 icon :<span class="lui-icon lui-icon--history"></span>'
&'<br>Line 4 5vw font :<span style="font-size:5vw;">EXAMPLE</span>'

&'<div style="height:50px;width:100px;background-color:#F3B7A1;padding:10px;">TEST DIV<div>'
&'<div style="height:50px;width:150px;background-color:#BBF0F8;margin:50px;text-align:center;">'
	&'TEST DIV with A<br><a href="https://www.qlik.com" target="_blank">qlik.com link</a>'
&'</div>'
&'<div style="height:100px;width:300px;background-color:#F2F5F5;padding:10px;">'
	&'TEST DIV with img <br><img src="https://qlik.imgix.net/us/-/media/images/qlik/global/qlik-logo-2x.png?h=94&w=308&la=en&hash=91B8028A8CF991CF3864E421063D49298BD58575">'
&'</div>'
```




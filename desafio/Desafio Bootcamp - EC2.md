<mxfile host="Electron" agent="Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) draw.io/28.1.2 Chrome/138.0.7204.243 Electron/37.4.0 Safari/537.36" version="28.1.2">
<diagram name="Página-1" id="t3mRRgpiZlYURtXxyLUK">
<mxGraphModel dx="2091" dy="1035" grid="1" gridSize="10" guides="1" tooltips="1" connect="1" arrows="1" fold="1" page="1" pageScale="1" pageWidth="1169" pageHeight="827" math="0" shadow="0">
<root>
<mxCell id="0"/>
<mxCell id="1" parent="0"/>
<mxCell id="Yf008zZsgp-P3UcssafK-40" value="" style="shape=cloud;whiteSpace=wrap;html=1;" vertex="1" parent="1">
<mxGeometry x="-70" y="10" width="910" height="720" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-1" value="" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.s3;fillColor=#E05243;gradientColor=none;" vertex="1" parent="1">
<mxGeometry x="340" y="270" width="76.5" height="93" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-26" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;" edge="1" parent="1" source="Yf008zZsgp-P3UcssafK-2" target="Yf008zZsgp-P3UcssafK-1">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-49" value="<strong>Faz o upload<br>para o S3</strong>&nbsp;" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Yf008zZsgp-P3UcssafK-26">
<mxGeometry x="-0.1049" relative="1" as="geometry">
<mxPoint as="offset"/>
</mxGeometry>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-2" value="" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.ec2;fillColor=#F58534;gradientColor=none;" vertex="1" parent="1">
<mxGeometry x="81.75" y="270" width="76.5" height="93" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-4" value="" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.volume;fillColor=#E05243;gradientColor=none;" vertex="1" parent="1">
<mxGeometry x="578.25" y="500" width="52.5" height="75" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-11" value="" style="outlineConnect=0;dashed=0;verticalLabelPosition=bottom;verticalAlign=top;align=center;html=1;shape=mxgraph.aws3.lambda_function;fillColor=#F58534;gradientColor=none;" vertex="1" parent="1">
<mxGeometry x="570" y="280" width="69" height="72" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-25" value="" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;flowAnimation=1;" edge="1" parent="1" source="Yf008zZsgp-P3UcssafK-24" target="Yf008zZsgp-P3UcssafK-2">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-30" value="<div>Acessa uma</div><div>&nbsp;interface web</div>" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Yf008zZsgp-P3UcssafK-25">
<mxGeometry x="-0.0762" y="-1" relative="1" as="geometry">
<mxPoint as="offset"/>
</mxGeometry>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-24" value="" style="verticalLabelPosition=bottom;aspect=fixed;html=1;shape=mxgraph.salesforce.web;fillColorStyles=fillColor2,fillColor3,fillColor4;fillColor2=#032d60;fillColor3=#0d9dda;fillColor4=#ffffff;fillColor=none;strokeColor=none;" vertex="1" parent="1">
<mxGeometry x="90" y="640" width="60" height="47.400000000000006" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-28" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0.5;entryY=0;entryDx=0;entryDy=0;entryPerimeter=0;flowAnimation=1;" edge="1" parent="1" source="Yf008zZsgp-P3UcssafK-11" target="Yf008zZsgp-P3UcssafK-4">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-39" value="Salvos no EBS" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Yf008zZsgp-P3UcssafK-28">
<mxGeometry x="-0.2297" y="1" relative="1" as="geometry">
<mxPoint as="offset"/>
</mxGeometry>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-29" value="Amazon EC2" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="1">
<mxGeometry x="75" y="240" width="90" height="30" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-31" value="<span style="color: rgb(255, 255, 255); font-family: Helvetica; font-size: 12px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: center; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: nowrap; background-color: rgb(27, 29, 30); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;">Amazon S3</span>" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
<mxGeometry x="350" y="240" width="100" height="40" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-32" style="edgeStyle=orthogonalEdgeStyle;rounded=0;orthogonalLoop=1;jettySize=auto;html=1;entryX=0;entryY=0.5;entryDx=0;entryDy=0;entryPerimeter=0;flowAnimation=1;" edge="1" parent="1" source="Yf008zZsgp-P3UcssafK-1" target="Yf008zZsgp-P3UcssafK-11">
<mxGeometry relative="1" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-35" value="Dispara um evento&nbsp;<div>(trigger)</div>" style="edgeLabel;html=1;align=center;verticalAlign=middle;resizable=0;points=[];" vertex="1" connectable="0" parent="Yf008zZsgp-P3UcssafK-32">
<mxGeometry x="-0.4091" y="-2" relative="1" as="geometry">
<mxPoint x="29" y="-2" as="offset"/>
</mxGeometry>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-34" value="AWS Lambda" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="1">
<mxGeometry x="550" y="248" width="100" height="30" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-38" value="<span style="color: rgb(255, 255, 255); font-family: Helvetica; font-size: 12px; font-style: normal; font-variant-ligatures: normal; font-variant-caps: normal; font-weight: 400; letter-spacing: normal; orphans: 2; text-align: center; text-indent: 0px; text-transform: none; widows: 2; word-spacing: 0px; -webkit-text-stroke-width: 0px; white-space: nowrap; background-color: rgb(27, 29, 30); text-decoration-thickness: initial; text-decoration-style: initial; text-decoration-color: initial; display: inline !important; float: none;">Amazon EBS</span>" style="text;whiteSpace=wrap;html=1;" vertex="1" parent="1">
<mxGeometry x="560" y="587.4" width="100" height="40" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-43" value="<font style="font-size: 24px;">AWS</font>" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="1">
<mxGeometry x="280" y="80" width="80" height="40" as="geometry"/>
</mxCell>
<mxCell id="Yf008zZsgp-P3UcssafK-45" value="<span style="font-family: __Inter_f367f3, __Inter_Fallback_f367f3, ui-sans-serif, system-ui, sans-serif, &quot;Apple Color Emoji&quot;, &quot;Segoe UI Emoji&quot;, &quot;Segoe UI Symbol&quot;, &quot;Noto Color Emoji&quot;; font-size: 20px; font-weight: 600; text-align: start; text-wrap-mode: wrap; background-color: rgb(9, 9, 11);">Sistema de Organização Pessoal</span>" style="text;html=1;align=center;verticalAlign=middle;resizable=0;points=[];autosize=1;strokeColor=none;fillColor=none;" vertex="1" parent="1">
<mxGeometry x="158.25" y="130" width="310" height="40" as="geometry"/>
</mxCell>
</root>
</mxGraphModel>
</diagram>
</mxfile>

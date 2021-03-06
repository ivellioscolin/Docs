DepthFloatFrame Constructor  
===========================  

Initializes a new instance of the [DepthFloatFrame](../DepthFloatFrame_Class.md) class. <span id="syntaxSection"></span>

Syntax  
======  

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C++</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public:  
DepthFloatFrame(  
         uint32 width,  
         uint32 height,  
         <a href="../CameraParameters_Structure.md">CameraParameters</a> cameraParameters  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">C#</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>public DepthFloatFrame (  
         uint width,  
         uint height,  
         <a href="../CameraParameters_Structure.md">CameraParameters</a> cameraParameters  
)</code></pre></td>
</tr>
</tbody>
</table>

<table>
<colgroup>
<col width="100%" />
</colgroup>
<thead>
<tr class="header">
<th align="left">JavaScript</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td align="left"><pre><code>var depthFloatFrame = new Microsoft.Kinect.Fusion.DepthFloatFrame(width, height, cameraParameters);</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EK"></span>
#### Parameters  

*width*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The width of the frame, in pixels.  

*height*    
[C++] Type: uint32  
  [C\#] Type: [uint](http://msdn.microsoft.com/en-us/library/system.uint32.aspx)  
  [JavaScript] Type: Number  
   

The height of the frame, in pixels.  

*cameraParameters*    
Type: [CameraParameters](../CameraParameters_Structure.md)  
The camera parameters associated with the frame.  

<span id="requirements"></span>

Requirements  
============  

**Namespace:**Microsoft.Kinect.Fusion  
**Metadata:**microsoft.kinect.fusion.winmd  

<span id="ID4EMB"></span>

See also  
========  

<span id="ID4EOB"></span>
#### Reference  

[DepthFloatFrame Class](../DepthFloatFrame_Class.md)  
 [Microsoft.Kinect.Fusion Namespace](../../Kinect.Fusion.md)  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : DepthFloatFrame Constructor
RLTitle : DepthFloatFrame Constructor
KeywordK : DepthFloatFrame class, constructor
KeywordK : DepthFloatFrame.DepthFloatFrame constructor
KeywordF : Microsoft.Kinect.Fusion.DepthFloatFrame.#ctor
KeywordF : Microsoft.Kinect.Fusion.DepthFloatFrame.DepthFloatFrame
KeywordF : Microsoft.Kinect.Fusion.DepthFloatFrame.New
KeywordF : Microsoft.Kinect.Fusion.DepthFloatFrame.#ctor(System.UInt32,System.UInt32,Microsoft.Kinect.Fusion.CameraParameters)
KeywordF : DepthFloatFrame.DepthFloatFrame
KeywordF : DepthFloatFrame.New
KeywordA : M:Microsoft.Kinect.Fusion.DepthFloatFrame.#ctor(System.UInt32,System.UInt32,Microsoft.Kinect.Fusion.CameraParameters)
AssetID : M:Microsoft.Kinect.Fusion.DepthFloatFrame.#ctor(System.UInt32,System.UInt32,Microsoft.Kinect.Fusion.CameraParameters)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : microsoft.kinect.fusion.winmd
APIName : Microsoft.Kinect.Fusion.DepthFloatFrame
TargetOS : Windows
TopicType : kbSyntax
DevLang : VB
DevLang : CSharp
DevLang : JavaScript
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

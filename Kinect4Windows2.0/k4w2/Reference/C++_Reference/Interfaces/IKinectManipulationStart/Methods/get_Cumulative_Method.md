IKinectManipulationStartedEventArgs::get\_Cumulative Method  
===========================================================  

Gets values that indicate the accumulated transformation deltas (translation, rotation, scale) for a manipulation before the ManipulationInertiaStarting event. <span id="syntaxSection"></span>

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
HRESULT get_Cumulative(  
         KinectManipulationDelta *value  
)</code></pre></td>
</tr>
</tbody>
</table>

<span id="ID4EG"></span>
#### Parameters  

*value*    
Type: KinectManipulationDelta  
[out] The accumulated transformation values up to the ManipulationInertiaStarting event.  

<span id="ID4EP"></span>
#### Return value  

Type: HRESULT  
Returns S\_OK if successful; otherwise, returns a failure code.  

<span id="requirements"></span>

Requirements  
============  

**Header:** kinect.h  
**Library:** TBD  



<!--Please do not edit the data in the comment block below.-->
<!--
TOCTitle : get_Cumulative Method
RLTitle : IKinectManipulationStartedEventArgs::get_Cumulative Method
KeywordK : get_Cumulative method
KeywordK : IKinectManipulationStartedEventArgs::get_Cumulative method
KeywordF : IKinectManipulationStartedEventArgs::get_Cumulative
KeywordF : get_Cumulative
KeywordF : Microsoft.Kinect.kinect.IKinectManipulationStartedEventArgs.get_Cumulative(KinectManipulationDelta@)
KeywordA : M:Microsoft.Kinect.kinect.IKinectManipulationStartedEventArgs.get_Cumulative(KinectManipulationDelta@)
AssetID : M:Microsoft.Kinect.kinect.IKinectManipulationStartedEventArgs.get_Cumulative(KinectManipulationDelta@)
Locale : en-us
CommunityContent : 1
APIType : Managed
APILocation : 
APIName : Microsoft.Kinect.kinect.IKinectManipulationStartedEventArgs::get_Cumulative
TargetOS : Windows
TopicType : kbSyntax
DevLang : C++
DocSet : K4Wv2
ProjType : K4Wv2Proj
Technology : Kinect for Windows
Product : Kinect for Windows SDK v2
productversion : 20
-->

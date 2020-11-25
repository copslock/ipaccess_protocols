# URSL is an enhanced RANAP including HNB management procedures                                 

**UserPlane**
<pre>
uRSLGetUserPlaneModifyResponseMsg
uRSLGetUserPlaneConfigResponseMsg
uRSLBuildUserPlaneModifyRequestMsg
uRSLBuildUserPlaneConfigRequestMsg
</pre>
**UeContext**
<pre>
uRSLBuildUeContextRequestMsg                                                       RNC → CN
uRSLBuildUeContextReleaseMsg                                                       RNC → CN
uRSLGetUeContextRejectMsg                                                          CN → RNC
uRSLGetUeContextAcceptMsg                                                          CN → RNC
</pre>
**SecurityMode**
<pre>
uRSLGetSecurityModeCommandMsg               SECURITY MODE COMMAND                  CN → RNC
uRSLBuildSecurityModeRejectMsg              SECURITY MODE REJECT                   RNC → CN
uRSLBuildSecurityModeCompleteMsg            SECURITY MODE COMPLETE                 RNC → CN
</pre>
**Reset**
<pre>
uRSLGetResetMsg                             RESET                                  CN → RNC
</pre>
**Relocation**
<pre>
uRSLGetRelocationFailureMsg                 =?RELOCATION PREPARATION FAILURE       CN → RNC    
uRSLGetRelocationCommandMsg                 RELOCATION COMMAND                     CN → RNC
uRSLBuildRelocationRequiredMsg              RELOCATION REQUIRED                    RNC → CN
uRSLBuildRelocationCancelMsg                RELOCATION CANCEL                      RNC → CN
</pre>
**RAB**
<pre>
uRSLGetRabAssignmentRequestMsg              RAB ASSIGNMENT REQUEST                 CN → RNC
uRSLBuildRabAssignmentResponseMsg           RAB ASSIGNMENT RESPONSE                RNC → CN
uRSLGetRabReleaseRequestMsg                                                        CN → RNC
uRSLBuildRabReleaseResponseMsg                                                     RNC → CN
uRSLBuildRabReleaseRequiredMsg              =?RAB RELEASE REQUEST                  RNC → CN
</pre>
**MessageId**
<pre>
uRSLGetMessageId
</pre>
**IuRelease**
<pre>
uRSLGetIuReleaseCommandMsg                 IU RELEASE COMMAND                      CN → RNC
uRSLBuildIuReleaseRequestMsg               IU RELEASE REQUEST                      RNC → CN
uRSLBuildIuReleaseCompleteMsg              IU RELEASE COMPLETE                     RNC → CN
</pre>
**InterfaceVersion**
<pre>
uRSLGetInterfaceVersion
</pre>
**Paging**
<pre>
uRSLGetIdleModePagingMsg                   PAGING                                  CN → RNC
uRSLGetConnectedModePagingMsg              PAGING                                  CN → RNC
</pre>
**IapReset**
<pre>
uRSLGetIapResetMsg                                                                 CN → RNC
uRSLBuildIapResetMsg                                                               RNC → CN
</pre>
**Handover**
<pre>
uRSLGetHandoverRequestMsg                 =?RELOCATION REQUEST/COMMAND             CN → RNC
uRSLGetHandoverCancelIndMsg               =?RELOCATION CANCEL ACKNOWLEDGE          CN → RNC
uRSLBuildHandoverReqAckMsg                =?RELOCATION REQUEST ACKNOWLEDGE         RNC → CN
uRSLBuildHandoverFailureMsg               =?RELOCATION FAILURE                     RNC → CN
uRSLBuildHandoverDetectMsg                =?RELOCATION DETECT/REQUIRED             RNC → CN
uRSLBuildHandoverCompleteMsg              =?RELOCATION COMPLETE                    RNC → CN
</pre>
**AccessControl**
<pre>
uRSLGetAccessControlResponseMsg                                                    CN → RNC
uRSLBuildAccessControlRequestMsg                                                   RNC → CN
</pre>
**DirectTransfer**
<pre>
uRSLGetDlDirectTransferMsg                DIRECT TRANSFER                         CN → RNC
uRSLBuildUlDirectTransferMsg              DIRECT TRANSFER                         RNC → CN                 
uRSLBuildInitDirectTransferMsg            DIRECT TRANSFER                         RNC → CN
</pre>

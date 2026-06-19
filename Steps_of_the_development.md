### 1. Agency F4 help / value help data should be appear from / fetch from company’s on-premise system and display data on the RAP App created in ABAP On Cloud BTP system. 

#### This is consuming External OData Service (From S/4 HANA ON-Premise system) in ABAP on Cloud.

<img width="940" height="414" alt="image" src="https://github.com/user-attachments/assets/86ed0c92-0814-4f02-86da-e41a98db16b7" />


<img width="940" height="435" alt="image" src="https://github.com/user-attachments/assets/e2a77c1a-88d5-4001-ae13-b0321db55d09" />


<img width="940" height="256" alt="image" src="https://github.com/user-attachments/assets/bd35cb69-d05d-45e8-9fee-5b319907f2a4" />


<img width="900" height="496" alt="image" src="https://github.com/user-attachments/assets/2fc9baea-0dc2-4e0d-8cd6-dbb22ddde007" />



### 2. Created package and the table ZAGENCIES in the on-premise S/4 HANA server. 
### Right Click on the table and say Generate ABAP Repository Objects and Created Entire RAP Application.

<img width="954" height="449" alt="image" src="https://github.com/user-attachments/assets/ab10ed0a-c8ec-40ce-86de-909981700c53" />


<img width="940" height="656" alt="image" src="https://github.com/user-attachments/assets/fa0a54aa-03f5-4a0f-af8d-c3ae4d639cca" />


<img width="940" height="696" alt="image" src="https://github.com/user-attachments/assets/42b60aa7-dc80-486c-a361-43eb025542e1" />


<img width="940" height="493" alt="image" src="https://github.com/user-attachments/assets/ad384258-6c43-492c-90d7-6c43cf43bb49" />


<img width="940" height="510" alt="image" src="https://github.com/user-attachments/assets/e682ece8-7ff0-4897-9bcd-7148ba9b44c9" />



#### Clicked on the Service URL:

<img width="940" height="234" alt="image" src="https://github.com/user-attachments/assets/2fb23a68-f2d4-454d-8525-4999cb66f55e" />


<img width="917" height="413" alt="image" src="https://github.com/user-attachments/assets/1a51be5e-5907-4574-bf48-f123a8d78ea7" />


#### Replace entity set name ‘ZATS_AB_C_AGENCIES’ with ‘?sap-client=800’:

<img width="819" height="366" alt="image" src="https://github.com/user-attachments/assets/10738556-efbc-4698-b564-995f5dfb3732" />


<img width="940" height="424" alt="image" src="https://github.com/user-attachments/assets/5a1addff-9f40-4a5d-b1fc-c2eccf213bd0" />


#### Entire data from the table ZAGENCIES got it in the form metadata in the json format.

<img width="940" height="788" alt="image" src="https://github.com/user-attachments/assets/c4532268-b100-4c53-a828-28c0e9fd6ef1" />



### 3. Now, how to replace this old agencies data with 7 series number agency id replace with newly generated agencies Z table 9 series agency id.

<img width="1129" height="588" alt="image" src="https://github.com/user-attachments/assets/e9223c3f-e36c-46a6-b622-41eef07ec89f" />


#### Download the metadata.

<img width="940" height="217" alt="image" src="https://github.com/user-attachments/assets/4135d2ec-d677-4470-8fdb-8dc7ed44402e" />


<img width="940" height="570" alt="image" src="https://github.com/user-attachments/assets/4384ebf1-4e75-4094-9e01-05aed69c0e7a" />


<img width="940" height="566" alt="image" src="https://github.com/user-attachments/assets/544b36b0-d48f-4de5-af7a-e87abbc983ac" />


<img width="940" height="202" alt="image" src="https://github.com/user-attachments/assets/df66ccbd-838d-4826-b7d2-8b874cd70b2d" />


### 4. Create a Service Consumption Model in the ABAP On Cloud:

<img width="1036" height="452" alt="image" src="https://github.com/user-attachments/assets/81bd5d77-b530-4c27-956a-4ec41badd7a5" />


<img width="940" height="564" alt="image" src="https://github.com/user-attachments/assets/6d5c06b3-419b-44d7-87a6-6dfe7b3cdaed" />


<img width="940" height="616" alt="image" src="https://github.com/user-attachments/assets/790a49d6-d353-4f39-a57d-bcaad64bba51" />


<img width="940" height="583" alt="image" src="https://github.com/user-attachments/assets/fb070b70-f694-47f4-8be6-d2fd14df899c" />


<img width="940" height="585" alt="image" src="https://github.com/user-attachments/assets/2df61215-7c83-4ee9-80ac-7c8a888f421d" />


<img width="940" height="584" alt="image" src="https://github.com/user-attachments/assets/359da3fe-223d-4ae3-b0fe-ebc046df4f90" />


<img width="940" height="439" alt="image" src="https://github.com/user-attachments/assets/d393e1de-6b38-45dc-ad66-8922bd88f6ed" />


<img width="940" height="444" alt="image" src="https://github.com/user-attachments/assets/9d829af3-2640-4ee2-833b-3155341bb03b" />


<img width="940" height="412" alt="image" src="https://github.com/user-attachments/assets/30d8bc0f-6071-4833-a3b9-f2263d9b29a0" />


#### Activate the Service Consumption Model. Operation: Read List and Copy to Clipboard.

<img width="940" height="428" alt="image" src="https://github.com/user-attachments/assets/8050f8f3-9ee7-4040-9ff0-6b7134d12d8f" />


### 5. Create Custom Entity in the ABAP On Cloud:

<img width="940" height="488" alt="image" src="https://github.com/user-attachments/assets/a3b88117-8ac0-421c-852c-a9977b69a687" />


<img width="940" height="473" alt="image" src="https://github.com/user-attachments/assets/b3611c6e-a216-4737-838e-0c60a8e69a97" />


<img width="940" height="567" alt="image" src="https://github.com/user-attachments/assets/a58b9f20-68e6-47ba-ab92-326820a192e9" />


<img width="940" height="458" alt="image" src="https://github.com/user-attachments/assets/999fde36-3ec4-4ca8-a81e-d492c444b9d2" />


<img width="940" height="346" alt="image" src="https://github.com/user-attachments/assets/17b526cd-582d-4701-8b2e-eed11af48a10" />


#### Created the class defined in the Custom Entity:


<img width="940" height="603" alt="image" src="https://github.com/user-attachments/assets/6a25cfb8-4c9a-4535-a48a-7411f301ea67" />


<img width="940" height="511" alt="image" src="https://github.com/user-attachments/assets/f8fdfbe5-4d4e-41dd-9c77-acd1f37d9c29" />



#### Table type replacement:


<img width="940" height="328" alt="image" src="https://github.com/user-attachments/assets/34bc35ef-add6-4ac1-af64-1ff6369b5eda" />


<img width="940" height="303" alt="image" src="https://github.com/user-attachments/assets/2691f7af-5e5e-4f5e-b297-9890d53f53e9" />


<img width="940" height="279" alt="image" src="https://github.com/user-attachments/assets/6ab948db-4b87-4e58-baac-42d7749c9977" />


<img width="940" height="333" alt="image" src="https://github.com/user-attachments/assets/ac1fdd3f-c43f-452f-abf5-aeb481a02975" />


<img width="940" height="258" alt="image" src="https://github.com/user-attachments/assets/bc94eb05-4d34-4921-9970-1d348f391cf8" />


<img width="940" height="276" alt="image" src="https://github.com/user-attachments/assets/9225a278-26fd-4bea-99d1-8fd2e6905556" />



#### Table type replacement completed:

<img width="940" height="276" alt="image" src="https://github.com/user-attachments/assets/ae04c878-ab95-4cc8-bf8f-30a995d586dd" />


#### Create http client---> If you have productive BTP account only then we can use the below commented code.

<img width="940" height="212" alt="image" src="https://github.com/user-attachments/assets/ec24357b-9b6d-4324-9738-78f76e02e876" />


#### Where, ‘S4HANA2’ Destination name:

<img width="940" height="519" alt="image" src="https://github.com/user-attachments/assets/37829437-2eb7-4b94-bbc6-b45c7e3145b2" />


#### Where, ‘mydest’ Service instance name:

<img width="940" height="216" alt="image" src="https://github.com/user-attachments/assets/7f063e8e-4109-4b3f-a64e-8d7d5672ab79" />


<img width="940" height="585" alt="image" src="https://github.com/user-attachments/assets/38bfd23e-48d4-4133-8fae-01bc061a45e3" />


#### If you are using BTP Trial Account then use the below code:---->

<img width="940" height="56" alt="image" src="https://github.com/user-attachments/assets/279adc7d-9127-46e6-a774-9b66a7d8cf76" />


#### Replaced the host name with ‘http://122.162.240.164:8010':

<img width="940" height="276" alt="image" src="https://github.com/user-attachments/assets/dc068d62-babc-4c58-a2ef-26b7816a83c5" />


<img width="940" height="280" alt="image" src="https://github.com/user-attachments/assets/9aa1f64a-de82-4d83-a1c5-840bc8d24c67" />


#### System will ask the credentials:


<img width="940" height="266" alt="image" src="https://github.com/user-attachments/assets/050af776-3fd7-4e84-8836-c894e5bc3d4f" />


#### Non-Productive BTP Accounts, we need to pass hardcoded auth data:
#### To avoid the above credentials, need to encrypt the credentials data. Therefore, use url: https://www.base64encode.org/
#### User:Password = abap9:welcome@88


<img width="940" height="645" alt="image" src="https://github.com/user-attachments/assets/80137575-149e-45b5-b7e6-7d60df615488" />


<img width="891" height="654" alt="image" src="https://github.com/user-attachments/assets/a71a9c65-d26e-4ab8-9099-c33956d03f5e" />


#### Copy the above encrypted data and keep the value like |Basic <above encrypted data>|. do not remove 'Basic'.


<img width="940" height="221" alt="image" src="https://github.com/user-attachments/assets/e10a7689-4494-4553-b495-12b427edc19a" />


<img width="940" height="195" alt="image" src="https://github.com/user-attachments/assets/0ab83361-afb4-48a0-937a-8ced5f02ad42" />


#### Replace proxy_model_id with your service consumption model name: ZATS_AB_AGENCY
#### " iv_relative_service_root - your OData V4 relative path


<img width="940" height="208" alt="image" src="https://github.com/user-attachments/assets/78eb238c-9728-4108-93a7-50aa7644dfb4" />


<img width="889" height="329" alt="image" src="https://github.com/user-attachments/assets/9b8d8f80-3987-448c-9170-aa7c25696219" />


<img width="940" height="210" alt="image" src="https://github.com/user-attachments/assets/a1ebdb15-4456-4dd8-89d0-3781708cea60" />


#### iv_relative_service_root - your OData V4 relative path:
#### Parameter in the method ‘CREATE_V4_REMOTE_PROXY’ for OData V4 / for OData V2 use method ‘CREATE_V2_REMOTE_PROXY’.


<img width="1134" height="193" alt="image" src="https://github.com/user-attachments/assets/2eafbff6-4c2d-48df-a83d-99b32ab2d695" />


<img width="1132" height="260" alt="image" src="https://github.com/user-attachments/assets/9c083ee9-2965-4e29-a018-5bd066bd0f3c" />


<img width="1141" height="164" alt="image" src="https://github.com/user-attachments/assets/e30ca4ad-737b-4776-b6c6-a718bc85fabd" />


#### Below screenshot from practicing the same use case:


<img width="1139" height="183" alt="image" src="https://github.com/user-attachments/assets/644cad33-9387-4742-8514-506642f44b1d" />


#### Navigate to the resource and create a request for the read operation
#### Your entityset name inside the service


<img width="940" height="96" alt="image" src="https://github.com/user-attachments/assets/c27698c8-a0fc-400d-b463-fc092e2500c0" />


<img width="940" height="199" alt="image" src="https://github.com/user-attachments/assets/ae688b67-42aa-451d-ab1f-f51dc2d40c2c" />


<img width="838" height="404" alt="image" src="https://github.com/user-attachments/assets/68cac019-eaaa-496c-91c2-b911ffde2d2a" />


<img width="940" height="101" alt="image" src="https://github.com/user-attachments/assets/f80d9dde-2d89-4e58-90ab-7df55115e16b" />


#### Finally, need to replace the Custom Entity name and its key field into root view entity where we have implemented value help for Agency in the ABAP On Cloud system:


<img width="940" height="346" alt="image" src="https://github.com/user-attachments/assets/eba11500-84c3-41bd-bb75-da289a9fee3b" />


<img width="940" height="461" alt="image" src="https://github.com/user-attachments/assets/079a9bae-408e-4800-bd23-764dda3e164a" />


<img width="940" height="527" alt="image" src="https://github.com/user-attachments/assets/7676c6f8-abb7-497d-8350-6e537c250b2e" />


<img width="940" height="393" alt="image" src="https://github.com/user-attachments/assets/1f2c4dbf-12df-456e-9272-8b90b1742a7e" />


<img width="940" height="827" alt="image" src="https://github.com/user-attachments/assets/ea117527-0d48-4cf4-bc48-6ad41be9979a" />


<img width="940" height="431" alt="image" src="https://github.com/user-attachments/assets/f3100458-c774-44e4-9217-1d1af99591df" />


<img width="940" height="500" alt="image" src="https://github.com/user-attachments/assets/2e7d8a17-5631-4d0f-b885-5ce597408edf" />


#### Consumption of an External OData service exercise has been completed.





























 






























































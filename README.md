# Healthcare_Content_API
An API to find healthcare content such as ICD9, ICD10, LOINC, RxNorm, HCPCS, MSDRG and many more.

<a href="http://www.mdguna.com">MDguna</a> is going to provide one stop shop for restful healthcare content. </br>
MDguna provides restfulAPIs for healthcare content such as diagnosis, procedures, MSDRG, HCPCS, LOINC, RxNorm and HCUPS
CCS. This platform provides APIs for ICD9 and ICD10 versions. </br>
MDguna would like to make it easy for developers to refrence helalthcare content with less or no effort. </br>
These APIs help developers and startups to focus on application rather than putting together content. </br>

</br><b>With the help of these APIs, you can find </b></br>
diagnosis name or code for ICD9 and ICD10, </br>
procedure name or code for ICD9 and ICD10, </br>
MSDRG name and code, </br>
HCPCS name and code, </br>
LOINC descprtions with code, </br>
RxNorm details,</br>
and HCUPS Clinical Classification details.</br>

You can also find content mapaping for </br>
MSDRG and ICD9 / ICD10, </br>
HCUPS CCS and ICD9 / ICD10, and many more to come in the future. </br>
 
You can test the API on our <a href="http://localhost:8100/#/page-API">website.</a></br>


Please refer to section below for guidelines on how to utilize the API.</br>
Base url: http://mdguna-env.qn5jr2pkqm.us-east-1.elasticbeanstalk.com/API </br>
Paramerts: </br>
1. <b>Contennt Type:</b> diagnosis, procedure, MSDRG, HCPCS
2. <b>Version:</b> ICD9, ICD10, None
3. <b>Search BY:</b> name, code
4. <b>Search Type:</b> contains, begins with, ends with
5. <b>Search String:</b> text

To seaarch an ICD9 diagnosis by name that contains Abdominal </br>
http://mdguna-env.qn5jr2pkqm.us-east-1.elasticbeanstalk.com/API/diagnosis/ICD9/name/contains/abdominal </br>

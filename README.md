# UploadFile
Adding the project to upload multiple fie in Share point
#Endpoint controller is problemmanagementservice controller where it consume the multipart file to upload the file in sharepoint repository location.
1.ProblemanagentServiceImpl class convert the file in base64 encoding to store the binary file in sharepoint network for adding security token using cloud enviorment to access sharepoint repository.
2.Download file from sharepoint by decoding the binary file using base64 decoder using java.
3.Project developed under spring-boot microservice architecture.

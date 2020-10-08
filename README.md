# Data View Mobile Push | Marketing Cloud

##### Data View _PushAddress 


| Field Name       | Data Type (Length) | Required (Y/N) | Data Default |
|------------------|--------------------|----------------|--------------|
| _ContactID       | Text               | Y              |              |
| _DeviceID        | Text(200)          | Y              |              |
| _APID            | Text(38)           | Y              |              |
| _Status          | Text               | N              |              |
| _Source          | Text               | N              |              |
| _SourceObjectId  | Text(200)          | N              |              |
| _Platform        | Text(100)          | N              |              |
| _PlatformVersion | Text(100)          | N              |              |
| _Alias           | Text(100)          | N              |              |
| _OptOutStatusID  | Text               | N              |              |
| _OptOutMethodID  | Text               | N              |              |
| _OptOutDate      | Date               | N              |              |
| _OptInStatusID   | Text               | Y              | 0            |
| _OptInMethodID   | Text               | N              |              |
| _OptInDate       | Date               | N              |              |
| _Channel         | Text(20)           | N              |              |
| _CreatedDate     | Date               | Y              | GETDATE()    |
| _CreatedBy       | Text               | N              |              |
| _ModifiedDate    | Date               | Y              | GETDATE()    |
| _ModifiedBy      | Text               | N              |              |
| _City            | Text(200)          | N              |              |
| _State           | Text(200)          | N              |              |
| _ZipCode         | Text(20)           | N              |              |
| _FirstName       | Text(100)          | N              |              |
| _LastName        | Text(100)          | N              |              |
| _UTCOffset       | Decimal(4,2)       | N              | 0            |
| _IsHonorDST      | Boolean            | N              | false        |
| _SystemToken     | Text(4000)         | N              |              |
| _ProviderToken   | Text(200)          | N              |              |
| _Badge           | Number             | N              |              |
| _LocationEnabled | Boolean            | N              |              |
| _TimeZone        | Text(50)           | N              |              |
| _Device          | Text(100)          | N              |              |
| _HardwareId      | Text(100)          | N              |              |
| _DeviceType      | Text(20)           | N              |              |


##### Data View _PushTag 


| Field Name    | Data Type (Length) | Required (Y/N) | Data Default |
|---------------|--------------------|----------------|--------------|
| _DeviceID     | Text(200)          | Y              |              |
| _APID         | Text(38)           | Y              |              |
| _Value        | Text(128)          | N              |              |
| _CreatedDate  | Date               | Y              | GETDATE()    |
| _CreatedBy    | Text               | N              |              |
| _ModifiedDate | Date               | Y              | GETDATE()    |
| _ModifiedBy   | Text               | N              |              |

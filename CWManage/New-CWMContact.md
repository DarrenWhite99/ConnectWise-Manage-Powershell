# New-CWMContact
## SYNOPSIS
This function will create a new contact.
## SYNTAX
```powershell
New-CWMContact [[-id] <Int32>] [-firstName] <String> [[-lastName] <String>] [[-type] <Object>] [[-company] <Object>] [[-site] <Object>] [[-addressLine1] <String>] [[-addressLine2] <String>] [[-city] <String>] [[-state] <String>] [[-zip] <String>] [[-country] <String>] [[-relationship] <Object>] [[-department] <Object>] [[-inactiveFlag] <Boolean>] [[-defaultMergeContactId] <Int32>] [[-securityIdentifier] <String>] [[-managerContactId] <Int32>] [[-assistantContactId] <Int32>] [[-title] <String>] 

[[-school] <String>] [[-nickName] <String>] [[-marriedFlag] <Boolean>] [[-childrenFlag] <Boolean>] [[-significantOther] <String>] [[-portalPassword] <String>] [[-portalSecurityLevel] <Int32>] [[-disablePortalLoginFlag] <Boolean>] [[-unsubscribeFlag] <Boolean>] [[-gender] <Object>] [[-birthDay] <String>] [[-anniversary] <String>] [[-presence] <Object>] [[-mobileGuid] <Guid>] [[-facebookUrl] <String>] [[-twitterUrl] <String>] [[-linkedInUrl] <String>] [[-defaultBillingFlag] <Boolean>] 

[[-defaultFlag] <Boolean>] [[-communicationItems] <Object>] [[-_info] <Object>] [[-customFields] <Object>] [<CommonParameters>]
```
## PARAMETERS
### -id &lt;Int32&gt;

```
Required                    false
Position                    1
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -firstName &lt;String&gt;

```
Required                    true
Position                    2
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -lastName &lt;String&gt;

```
Required                    false
Position                    3
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -type &lt;Object&gt;

```
Required                    false
Position                    4
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -company &lt;Object&gt;

```
Required                    false
Position                    5
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -site &lt;Object&gt;

```
Required                    false
Position                    6
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -addressLine1 &lt;String&gt;

```
Required                    false
Position                    7
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -addressLine2 &lt;String&gt;

```
Required                    false
Position                    8
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -city &lt;String&gt;

```
Required                    false
Position                    9
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -state &lt;String&gt;

```
Required                    false
Position                    10
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -zip &lt;String&gt;

```
Required                    false
Position                    11
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -country &lt;String&gt;

```
Required                    false
Position                    12
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -relationship &lt;Object&gt;

```
Required                    false
Position                    13
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -department &lt;Object&gt;

```
Required                    false
Position                    14
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -inactiveFlag &lt;Boolean&gt;

```
Required                    false
Position                    15
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -defaultMergeContactId &lt;Int32&gt;

```
Required                    false
Position                    16
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -securityIdentifier &lt;String&gt;

```
Required                    false
Position                    17
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -managerContactId &lt;Int32&gt;

```
Required                    false
Position                    18
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -assistantContactId &lt;Int32&gt;

```
Required                    false
Position                    19
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -title &lt;String&gt;

```
Required                    false
Position                    20
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -school &lt;String&gt;

```
Required                    false
Position                    21
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -nickName &lt;String&gt;

```
Required                    false
Position                    22
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -marriedFlag &lt;Boolean&gt;

```
Required                    false
Position                    23
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -childrenFlag &lt;Boolean&gt;

```
Required                    false
Position                    24
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -significantOther &lt;String&gt;

```
Required                    false
Position                    25
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -portalPassword &lt;String&gt;

```
Required                    false
Position                    26
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -portalSecurityLevel &lt;Int32&gt;

```
Required                    false
Position                    27
Default value                0
Accept pipeline input       false
Accept wildcard characters  false
```
### -disablePortalLoginFlag &lt;Boolean&gt;

```
Required                    false
Position                    28
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -unsubscribeFlag &lt;Boolean&gt;

```
Required                    false
Position                    29
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -gender &lt;Object&gt;

```
Required                    false
Position                    30
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -birthDay &lt;String&gt;

```
Required                    false
Position                    31
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -anniversary &lt;String&gt;

```
Required                    false
Position                    32
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -presence &lt;Object&gt;

```
Required                    false
Position                    33
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -mobileGuid &lt;Guid&gt;

```
Required                    false
Position                    34
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -facebookUrl &lt;String&gt;

```
Required                    false
Position                    35
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -twitterUrl &lt;String&gt;

```
Required                    false
Position                    36
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -linkedInUrl &lt;String&gt;

```
Required                    false
Position                    37
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -defaultBillingFlag &lt;Boolean&gt;

```
Required                    false
Position                    38
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -defaultFlag &lt;Boolean&gt;

```
Required                    false
Position                    39
Default value                False
Accept pipeline input       false
Accept wildcard characters  false
```
### -communicationItems &lt;Object&gt;

```
Required                    false
Position                    40
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -_info &lt;Object&gt;

```
Required                    false
Position                    41
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
### -customFields &lt;Object&gt;

```
Required                    false
Position                    42
Default value
Accept pipeline input       false
Accept wildcard characters  false
```
## EXAMPLES
### EXAMPLE 1
```powershell
PS C:\>New-CWMContact -firstName 'Chris' -lastName 'Taylor' -company @{id = $Company.id}

Create a new contact.
```

## NOTES
Author: Chris Taylor

Date: 10/10/2018 
## LINKS
http://labtechconsulting.com

https://developer.connectwise.com/manage/rest?a=Company&e=Contacts&o=CREATE

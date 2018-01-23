# Edugain Authentication source
## Required
- eduPersonScopedAffiliation
- eduPersonTargetedID

## Optional
- eduPersonPrincipalName
- mail
- cn
- sn
- givenName


# Facebook attribute map
| Facebook attribute  | up2u attribute      |
|---------------------|---------------------|
| facebook_first_name  | givenName           |
| facebook_last_name  | sn                  |
| facebook_email      | mail                |
| facebook_targetedID | eduPersonTargetedID |
| facebook_name       | displayName         |

# Google attribute map
| Google attribute    | up2u attribute      |
|---------------------|---------------------|
| name                | cn                  |
| given_name          | givenName           |
| family_name         | sn                  |
| name                | displayName         |
| mail                | mail                |
| profile              | labeledURI          |
| preferredLanguage   | preferredLanguage   |

# Twitter attribute map


# Selfregister attribute map
| Selfregister      |  up2u attribute       |
|-------------------|-----------------------|
| username          |  uid                  |  
| firstname          |  givenName            |
| lastname          |  sn                   |
| email             |  mail                 |

# Available Up2U Attributes:

- uid
- mail
- eduPersonScopedAffiliation
- eduPersonPrincipalName

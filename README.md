# GAWL: Golang API Wrapper for LinkedIn

---

GAWL (an acronym for `Golang API Wrapper - LinkedIn`) allows for simple access to LinkedIn's API with only a single dependency.

## Installation

TBD.

## Examples

Examples are provided in [docs/examples](docs/examples).

## Quickstart

```golang

// TBD

```

#### GET PROFILE:

TBD.

```golang

// TBD

/* response
{
    'localizedLastName': 'LAST_NAME',
    'profilePicture': {
        'displayImage': 'PHOTO_ID'
    },
    'firstName': {
        'localized': {
            'LANG_CODE_COUNTRY_CODE': 'FIRST_NAME'
        },
        'preferredLocale': {
            'country': 'COUNTRY_CODE_VALUE',
            'language': 'LANGUAGE_CODE'
        }
    },
    'lastName': {
        'localized': {
            'LANG_CODE_COUNTRY_CODE':
            'LAST_NAME'
        },
        'preferredLocale': {
            'country': 'COUNTRY_CODE',
            'language': 'LANGUAGE_CODE'
        }
    },
    'id': 'USER_ID',
    'localizedFirstName': 'LOCALIZED_FIRST_NAME'
}
*/
```

## Sources

Rewritten for Golang from PAWL.

## License

GAWL's source is provided under the MIT License.

- Copyright © 2021 Kyle J. Burda

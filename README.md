- 👋 Hi, I’m @liamtohacode
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
liamtohacode/liamtohacode is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  --method DELETE \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /orgs/ORG/actions/permissions/repositories/REPOSITORY_ID# GitHub CLI api
# https://cli.github.com/manual/gh_api

gh api \
  -H "Accept: application/vnd.github+json" \
  -H "X-GitHub-Api-Version: 2022-11-28" \
  /metacurl -L \
  -H "Accept: application/vnd.github+json" \
  -H "Authorization: Bearer <YOUR-TOKEN>"\
  -H "X-GitHub-Api-Version: 2022-11-28" \
  https://api.github.com/meta{
  "title": "Api Overview",
  "description": "Api Overview",
  "type": "object",
  "properties": {
    "verifiable_password_authentication": {
      "type": "boolean",
      "examples": [
        true
      ]
    },
    "ssh_key_fingerprints": {
      "type": "object",
      "properties": {
        "SHA256_RSA": {
          "type": "string"
        },
        "SHA256_DSA": {
          "type": "string"
        },
        "SHA256_ECDSA": {
          "type": "string"
        },
        "SHA256_ED25519": {
          "type": "string"
        }
      }
    },
    "ssh_keys": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "ssh-ed25519 ABCDEFGHIJKLMNOPQRSTUVWXYZ"
      ]
    },
    "hooks": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "web": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "api": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "git": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "packages": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "pages": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "importer": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "actions": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    },
    "dependabot": {
      "type": "array",
      "items": {
        "type": "string"
      },
      "examples": [
        "192.0.2.1"
      ]
    }
  },
  "required": [
    "verifiable_password_authentication"
  ]
}curl --request POST \
--url "https://api.github.com/authorizations"
--user CLIENT_ID:CLIENT_SECRET \
--header "X-GitHub-Api-Version: 2022------BEGIN RSA PRIVATE KEY-----
EXAMPLEKEYKCAQEAy7WZhaDsrA1W3mRlQtvhwyORRX8gnxgDAfRt/gx42kWXsT4rXE/b5CpSgie/
vBoU7jLxx92pNHoFnByP+Dc21eyyz6CvjTmWA0JwfWiW5/akH7iO5dSrvC7dQkW2duV5QuUdE0QW
Z/aNxMniGQE6XAgfwlnXVBwrerrQo+ZWQeqiUwwMkuEbLeJFLhMCvYURpUMSC1oehm449ilx9X1F
G50TCFeOzfl8dqqCP6GzbPaIjiU19xX/azOR9V+tpUOzEL+wmXnZt3/nHPQ5xvD2OJH67km6SuPW
oPzev/D8V+x4+bHthfSjR9Y7DvQFjfBVwHXigBdtZcU2/wei8D/HYwIDAQABAoIBAGZ1kaEvnrqu
/uler7vgIn5m7lN5LKw4hJLAIW6tUT/fzvtcHK0SkbQCQXuriHmQ2MQyJX/0kn2NfjLV/ufGxbL1
mb5qwMGUnEpJaZD6QSSs3kICLwWUYUiGfc0uiSbmJoap/GTLU0W5Mfcv36PaBUNy5p53V6G7hXb2
bahyWyJNfjLe4M86yd2YK3V2CmK+X/BOsShnJ36+hjrXPPWmV3N9zEmCdJjA+K15DYmhm/tJWSD9
81oGk9TopEp7CkIfatEATyyZiVqoRq6k64iuM9JkA3OzdXzMQexXVJ1TLZVEH0E7bhlY9d8O1ozR
oQs/FiZNAx2iijCWyv0lpjE73+kCgYEA9mZtyhkHkFDpwrSM1APaL8oNAbbjwEy7Z5Mqfql+lIp1
YkriL0DbLXlvRAH+yHPRit2hHOjtUNZh4Axv+cpg09qbUI3+43eEy24B7G/Uh+GTfbjsXsOxQx/x
p9otyVwc7hsQ5TA5PZb+mvkJ5OBEKzet9XcKwONBYELGhnEPe7cCgYEA06Vgov6YHleHui9kHuws
ayav0elc5zkxjF9nfHFJRry21R1trw2Vdpn+9g481URrpzWVOEihvm+xTtmaZlSp//lkq75XDwnU
WA8gkn6O3QE3fq2yN98BURsAKdJfJ5RL1HvGQvTe10HLYYXpJnEkHv+Unl2ajLivWUt5pbBrKbUC
gYBjbO+OZk0sCcpZ29sbzjYjpIddErySIyRX5gV2uNQwAjLdp9PfN295yQ+BxMBXiIycWVQiw0bH
oMo7yykABY7Ozd5wQewBQ4AdSlWSX4nGDtsiFxWiI5sKuAAeOCbTosy1s8w8fxoJ5Tz1sdoxNeGs
Arq6Wv/G16zQuAE9zK9vvwKBgF+09VI/1wJBirsDGz9whVWfFPrTkJNvJZzYt69qezxlsjgFKshy
WBhd4xHZtmCqpBPlAymEjr/TOlbxyARmXMnIOWIAnNXMGB4KGSyl1mzSVAoQ+fqR+cJ3d0dyPl1j
jjb0Ed/NY8frlNDxAVHE8BSkdsx2f6ELEyBKJSRr9snRAoGAMrTwYneXzvTskF/S5Fyu0iOegLDa
NWUH38v/nDCgEpIXD5Hn3qAEcju1IjmbwlvtW+nY2jVhv7UGd8MjwUTNGItdb6nsYqM2asrnF3qS
VRkAKKKYeGjkpUfVTrW0YFjXkfcrR/V+QFL5OndHAKJXjW7a4ejJLncTzmZSpYzwApc=
-----END RSA PRIVATE KEY-----

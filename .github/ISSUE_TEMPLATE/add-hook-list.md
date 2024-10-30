---
name: Add Token List
about: Add a list to tokenlist.org
title: 'Request: add {List name}'
labels: list-request
assignees: ''

inputs:
  url:
    description: 'List URL must be HTTPS, IPFS or ENS.'
    required: true
    default: ''
  list_name:
    description: 'List Name'
    required: true
    default: ''
  homepage:
    description: 'Link to the official homepage of the list manager'
    required: false
    default: ''

---

Before submission delete this line:
**THIS IS NOT A TOKEN LISTING REQUEST FORM. IF YOU DO NOT FOLLOW THE FORMAT OR MAKE A GENERIC TOKEN REQUEST YOUR ISSUE WILL BE DELETED WITHOUT COMMENT**

**YOU MUST FOLLOW THE JSON SPECIFICATION**

https://github.com/Uniswap/token-lists

Checklist
- [ ] **I understand that this is not the place to request token listing.**
- [ ] I have tested that my list is compatible by pasting the url into the `add a list` UI at `app.uniswap.org`.
- [ ] I understand that filing an issue or adding liquidity does not guarantee addition to the token list website.
- [ ] I will not ping the Discord about this listing request.

**Please provide the following information for your token.**

List URL: ${{ inputs.url }}
List Name: ${{ inputs.list_name }}
Link to the official homepage of the list manager: ${{ inputs.homepage }}
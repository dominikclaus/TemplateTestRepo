# Pull Request Template

#### Do not edit/commit this template

### Steps to Follow

- Create your PR
- Copy this file contents to the PR description
- Update your changes there and publish it

------------------   -------------------------------------------------------
JIRA LINK           | https://karstadt.atlassian.net/browse/WEB-950         |
------------------   -------------------------------------------------------

## Configuration Changes
### Please provide the information about any changes to Business Manager
------------------   ----------------  -------------------------------------
BM Config Edited    |  Name             |   Attribute added                    |
-------------------  ----------------  -------------------------------------
System Object       |  Product          |   exclude-product-from-regular-search|
------------------- -----------------  ------------------------------------
System Object       |  Site Preference  |   chanel-search-result-keywords      |
------------------  -----------------  -------------------------------------
Search Refinement (By attribute)|   Exclude product from regular search|   Exclude product  from regular search  |
------------------  -----------------  -------------------------------------

## Unit Test coverage:

Used adidas as chanel products

1. Only products with attribute value "true" for custom attribute "exclude-product-from-regular-search"
visible on SF when adidas added as search term to custom preference.

2. All products displayed excluding products with  custom attribute "exclude-product-from-regular-search" set to
    "true"

3. All sorting rules displayed and working fine.
4. Product tiles clickable.
5. This refinement not displayed on SF.

## Regression areas:
1. Search
2. CLP/PLP
3. Sorting
4. Refinements

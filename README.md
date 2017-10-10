# AEM Breadcrumb sample

This is an AEM 6.3 reference implementation for the breadcrumb component

## How to build

Install the package aem-jpmc-breadcrumb-1.0.zip using the AEM package manager.

## Implementation

- The OOTB breadcrumbs component from the core has been extended to include  option to make it editable.
- This is only a representation and not a fully functional compunent.
- The behaviour of the dialog can be made more dynamic by including Javascript/AJAX in the clientlibs
- The default behaviour on the component would get the elements of the current tree.
- This implementation would require the content user to edit each page to have a custom breadcrumb trail

## Alternative Approach
- Manage a seperate navigation tree can be used to handle navigation and would represent the sitemap and bresdcrumb more appropriately.
- Content user will not have to edit every page in the section of a site to make breadcrum changes
- The breadcrumb compoment will read elements from the navigation tree dynamically. 




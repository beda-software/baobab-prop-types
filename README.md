[![npm version](https://badge.fury.io/js/baobab-prop-types.svg)](https://badge.fury.io/js/baobab-prop-types)

baobab-prop-types
=========

React PropTypes for Baobab


## Installation

  npm install baobab --save
    
  npm install baobab-prop-types --save

## Usage

```
  import BaobabPropTypes from 'baobab-prop-types';
  
  ...
  
  propTypes: {
    field: BaobabPropTypes.cursor,
    reqField: BaobabPropTypes.cursor.isRequired,
    fieldTree: BaobabPropTypes.baobab,
    reqFieldTree: BaobabPropTypes.baobab.isRequired
  }
  ...
```

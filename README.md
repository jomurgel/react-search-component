# React Search Component
A search component for react.

## Usage
``` javascript
import Search from '../../components/search';

// Component usage.
<Search onQueryChange={ this.returnData } />

// Use dat as array.
returnData( response) {
    this.setState( { data: response } );
}
```

## Info
This component will run a WP search in posts and return an array value of data up through props.

A slightly older itteraction (but functionally the same) can be seen in action [here](https://codepen.io/jomurgel/pen/MVjdgW?editors=0010).

## Taro Sortable List

### Demo

![DEMO](https://github.com/LIU9293/taro-sortable-list/blob/master/demo.gif?raw=true)

### Install

```
yarn add taro-sortable-list
```

### Usage

``` JavaScript
// page.js
import SortableList from 'taro-sortable-list'

const data = [
  { id: 1, text: 'abc'},
  { id: 2, text: 'def'}
]

export default function MyPage () {
  return (
    <SortableList data={data} onSort={onSort} />
  )
}
```
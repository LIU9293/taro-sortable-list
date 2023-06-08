## Taro Sortable List

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
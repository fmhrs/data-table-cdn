# data-table-cdn
biar gak pusing masang library data table. cukup copy paste semuanya di header paling bawah.

```html
  <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>
  <script src="https://cdn.datatables.net/1.13.1/js/jquery.dataTables.min.js" defer></script>
  <script src="https://cdn.datatables.net/2.0.2/js/dataTables.js"></script>
  <script src="https://cdn.datatables.net/2.0.2/js/dataTables.bootstrap5.js"></script>
  
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/5.3.0/css/bootstrap.min.css">
  <link rel="stylesheet" href="https://cdn.datatables.net/2.0.2/css/dataTables.bootstrap5.css"/>
  <link rel="stylesheet" href="https://cdn.datatables.net/1.13.1/css/jquery.dataTables.min.css"/>
```
jika menggunakan darkmode mungkin akan error pada background select datatable yang berwarna putih dan bertulisan putih. untuk memperbaikinyna gunakan style
```css
div.dataTables_length > label > select > option {
    background: var(--bs-body-bg) !important;
}
```

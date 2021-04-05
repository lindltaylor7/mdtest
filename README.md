<!--Hedings-->


# Mi titulo
## Mi titulo h2
### Mi titulo h3
#### Mi titulo h4
##### Mi titulo h5
###### Mi titulo h6

<!--Italic-->
Texto en *italica*
<!--Strong-->
Texto en **strong**
<!--Strikethrough-->
Texto ~~tachado~~

<!--Ul-->

* apple
    * apple 2
* orange
    *orange
* etc.

1. apple
    1. apple 2
2. orange
    1. orange 3
3. etc

[google.com](https://www.google.com)

[google.com](https://www.google.com "Custom title")

>Esta es una cita

---
___
`console.log('hello world')`

```php
@extends('adminlte::page')

@section('title', 'Dashboard')

@section('content_header')
<a href="{{route('admin.certificados.create')}}" class="btn btn-secondary btn-sm float-right">Nuevo Certificado</a>
    <h1>Certificados</h1>

@stop

@section('content')
    <p>Tabla de Certificados.</p>

    @livewire('admin.certificado-index')
@stop

```

```html
<h1>hola mundo</h1>
```
|asddasads  |dasdasd    |
|---------  |-----------|
|asdas      |dasas      |
|col2       |col3       |

![vs code logo](vscode.jfif "VSCODE logo")

<!--Github md-->

* [x] Task 1
* [x] Task 2
* [] Task 3
* [] Task 4


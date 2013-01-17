
# attr

  Cross-browser attribute manipulation.

## Installation

    $ component install matthewp/attr

## Examples

    attr(el).get('id'); // -> foo
	attr(el).set('id', 'foo'); // -> undefined

## API

### attr(el)

Returns a new instance of ``Attr``.

### Attr

An object for manipulation of attributes on an element.

#### Attr#get(name)

Gets the attribute ``name`` as a string.

#### Attr#set(name, val)

Sets the attribute ``name`` to ``val``.

## License

  MIT

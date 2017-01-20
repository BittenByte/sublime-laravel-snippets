# Sublime Laravel Snippets

[![Software License][ico-license]](LICENSE.md)

This is where your description should go. Try and limit it to a paragraph or two, and maybe throw in a mention of what
PSRs you support to avoid any confusion with users and contributors.

## Install

Copy the `snippets` folder of this project into your Sublime Text Packages folder

## Usage

This repository contains a set of useful *snippets* that might ease the development of Laravel Products. Check [Snippets Documentation](http://docs.sublimetext.info/en/latest/extensibility/snippets.html) for more information.

### Laravel general snippets

- `met`: Creates a method within a class
- `pmet`: Protected method
- `smet`: Static function
- `test`: Creates a test function
- `irepository`: Creates a Repository Interface (for projects that use the Repository Pattern) - extends CrudRepository Interface
- `repository`: Creates an Eloquent Repository Implementation - implements Repository Interface, extends Eloquent Crud Repository
- `request`: Creates a Request class

### Laravel Model attributes

- `appends`: $appends atrribute (for accessors)
- `with`: $with attribute
º
### Form group

A set of snippets for blade form-groups

- `fg`: Any kind of input inside form group
- `fg-text`: Text input inside form group
- `fg-date`: Date input inside form group
- `fg-select2`: Select2 input inside form group

### Migration helpers

- `db-string`: New *string* column
- `db-text`: New *text* column
- `db-fk`: New *foreign key* column
- `db-boolean`: New *boolean* column


###

## Change log

## Contributing

Please see [CONTRIBUTING](CONTRIBUTING.md) and [CONDUCT](CONDUCT.md) for details.

## Credits

- [José Cámara <jm@bittenbyte.io](https://github.com/josec89)
- [All Contributors][link-contributors]

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.

# jsonschema

Simple and fast JSON schema

## Usage

	var v = new Validator();
	var instance = 4;
	var schema = {"type": "number"};
	console.log(v.validate(instance, schema));
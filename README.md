django-query-json-serializer
============================

I dug this out of web archive and it fit my needs for API creation.

The original author and his site is n/a and this is a great piece of code. I will maintain this code.

Original reference and discovery notes are in the in the comments.

### Usage ###

from JSONSerializer import JSONSerializer

z = JSONSerializer()

json_encoded_string = z.serialize(DjangoQuerySet)

Works on other Python data types as well. Love this lib!

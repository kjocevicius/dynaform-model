[![Build Status](https://travis-ci.org/teraxas/dform-compiler.svg?branch=master)](https://travis-ci.org/teraxas/dform-compiler)

# dynaform-ng dynamic forms compiler

This is a nodeJS lib for building finalized JSON objects of forms.
Mostly it includes resources, such as classifiers, to form objects.

## DFormCompiler

Compiler's constructor requires IResourceProvider object.
Then just use `compile(form: DForm)` method to compile form.


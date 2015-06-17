To improve your productivity, protobuf-dt offers content-based proposals based on

### Grammar ###

These proposals are based on the protobuf grammar. The following screenshot shows proposals based on keywords:

![http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-grammar.png](http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-grammar.png)

Proposals are not restricted to keywords only. For example, they can also include other elements in the grammar, such as the types for a message element (both built-in and user-defined)

![http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-field-type.png](http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-field-type.png)

### Context ###

In the following example, protobuf-dt proposes `[default = ]` because the message element being created is `optional`:

![http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-context.png](http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-context.png)

Another example of context-based proposals is `[packed = true]` when the message element being created is `repeated` and is of primitive type.

## Data type ##

These proposals are based on data type (e.g. `message` element or `option`.) In the following example, protobuf-dt proposes `true` and `false` because the element being created is of type `bool`:

![http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-type.png](http://wiki.protobuf-dt.googlecode.com/git/images/content-assist-type.png)


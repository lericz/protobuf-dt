protobuf-dt wants to save you time and energy as much as possible. Out of the box, it can automatically generate numeric tags as you type.

To have protobuf-dt generate the numeric tag of a `message` field or an `enum` literal, simply stop typing after you enter the name of the element and press semicolon:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=LnV2EN8-8io' target='_blank'><img src='http://img.youtube.com/vi/LnV2EN8-8io/0.jpg' width='425' height=344 /></a>

voilà! a new numeric tag is generated!

#### New in v1.0.1 ####

In long .proto files, it is common to have track the "next numeric tag" in a comment. Every time a message field is added, the developer making the change has to manually update such comment as well, something that is way too easy to forget.

This new version includes support for updating the "next numeric tag" comment automatically, when a numeric tag is generated:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=uq6ztmihiSQ' target='_blank'><img src='http://img.youtube.com/vi/uq6ztmihiSQ/0.jpg' width='425' height=344 /></a>

This change uses regular expressions to match the comment to update. By default it uses the pattern "Next[\s]+Id:[\s]+[\d]+", but more patterns can be added via a preference page.




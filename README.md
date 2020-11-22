# Larger post avatars

A Discourse theme component for easily changing the size of post avatars on Desktop, and the shape of avatars across the whole forum.

Also contains a setting that allows you to add some spacing between the avatar and the post content, which may be required to achieve a balanced layout when larger avatars are being used.

**Why create another theme component when discourse-avatar-component exists?**

Good question! See [discourse-avatar-component](https://github.com/discourse/discourse-avatar-component) for a more fully-featured theme component that also allows you to change the size of mobile avatars.

For my forum, I only wanted to increase the size of avatars on desktop browsers without loading larger images on mobile devices, and I only wanted to increase the size of avatars on topic pages, nowhere else.
I also needed a way to increase the spacing next to the avatar as I increased its size – I could've done it with some custom CSS, but having all the avatar-related settings in one place made more sense to me.

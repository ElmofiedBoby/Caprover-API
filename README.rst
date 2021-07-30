Original: https://github.com/Ak4zh/Caprover-API

This branch is not maintained and is only being used for a private project.

Only change is that it forces port mappings within Caprover to be read as a string rather than an array/dictionary since that was not working. If you require multiple port mappings on a single application you will not be able to do that at once - you'll need to call the caprover update method multiple times.

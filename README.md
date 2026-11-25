CI wrapper around https://github.com/Souls-R/celeste-ipados (native .NET AOT + Metal Celeste for iPadOS).
Game files are NOT in this repo: the `inputs` release only holds AES-256 encrypted blobs (key in a repo secret).
Output: workflow artifact `ipa` (unsigned, private to the build).

# burendo-githooks
Default Git hooks for Burendo repositories


### pre-commit

A pre-commit is designed to catch any secret/private content being accidently commited to public repositories. These include AWS Account IDs, Access key IDs, IP addresses, email addresses etc... This can been adjusted to ignore lines beginning Subproject commit to avoid triggering its own pre-commit check ("40 character random (e.g. AWS secret access key, PAT)").
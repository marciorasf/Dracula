# How to publish a new version

1. Install VSCE

	```bash
	npm install -g vsce
	```

2. Login VSCE

	```bash
	# It will ask for a Personal Access Token from Azure DevOps.
	vsce login marciorasf
	```

3. Packaging

	```bash
	vsce package
	```

4. Publish

	```bash
	# Patch can be replaced with "minor" or "major".
	vsce publish patch
	```
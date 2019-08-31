This is a demo dataset to demonstrate use of ///repronim/containers and YODA
principles to provide a DataLad dataset (git/git-annex repository).  The "script"
used to produce it was:

	#!/bin/bash

	set -eu

	# A demo from repronim/containers' README.md

	# Create output dataset
	datalad create -d data/ds000003-qc -c text2git
	cd data/ds000003-qc
	# Install our containers collection:
	datalad install -d . http://github.com/ReproNim/containers
	# Install input data:
	datalad install -d . -s https://github.com/ReproNim/ds000003-demo sourcedata
	# Execute desired preprocessing while creating a provenance record
	# in git history
	datalad containers-run \
			-n containers/bids-mriqc \
			--input sourcedata \
			--output . \
			'{inputs}' '{outputs}' participant group

and also present in the documentation of the https://github.com/ReproNim/containers.

all: py cropcentered dfgen k2g v2m

cropcentered:
	$(MAKE) -C CropCentered

dfgen:
	$(MAKE) -C DFGen

k2g:
	$(MAKE) -C Keypoints2Grid

v2m:
	$(MAKE) -C Vox2Mesh

py:
	for module in $(shell cat Script/requirements.txt); \
		do pip3 install $${module}; \
	done

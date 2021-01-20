
########### install files ###############

# install DSO catalog and textures
INSTALL(DIRECTORY ./ DESTINATION ${SDATALOC}/nebulae/default
	FILES_MATCHING 
	PATTERN "*.dat"
        PATTERN "*.jpg"
	PATTERN "*.json"
	PATTERN "CMakeFiles" EXCLUDE )

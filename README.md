zip -r myarchive.zip myfile_or_folder
split -b 50m myarchive.zip chunk_



cat chunk_* > combined.zip
unzip combined.zip

# blmdecoder
BLM Decoder to process blm files into a workable php array/object

# Instructions
Simply include the class and run:
$blm = new phpblm("YOURFILELOCATION/file.blm");

# See the results
foreach ($blm->properties() as $properties) {
    print_r($properties);
}


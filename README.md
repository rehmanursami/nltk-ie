# nltk-ie
NLTK-based Information Extraction for sample BTS data


#### Installation ####
1. Run the command: "bash run-install.sh" 
	This will install all the required packages.
	It will also download the required NLTK data (more than 1GB in size).


#### Description ####
This is an NLTK-based implementation intended to perform "Information Extraction" (item, quantity, comment) on sample BTS data.

The main code is in "infoext_v8.py". However, "dictSubjects.txt" and "my_pwl.txt" are dictionaries, accessed by the program in the process.

The program is run using: python infoext_v8.py [ocr_txtfile_output_from_omnipage]
e.g. python infoext_v8.py sample.txt

It will create a json file (with the same basename as the input_file and an extension of .nltk.json), with each object containing "Comment", "Input String", "Item" and "Quantity". In order to view the format of the json output, you can copy-paste the json output into this link <http://json.parser.online.fr>.





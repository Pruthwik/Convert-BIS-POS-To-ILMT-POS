# How to run the code
python convert_bis_to_ilmt_pos_tag.py --input sample-hin-BIS.txt --map bis_to_ilmt.json --output sample-hin-ilmt.txt

# input file should be in conll format, each line is of the format "token\tBIS-tag" and lines are separated by a blank line.
# bis_to_ud contains the mapping from BIS to ILMT POS tagset
# output file will be generated in the same format "token\tILMT-tag" and lines are separated by a blank line.

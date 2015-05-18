# Python-read_file
#read a file and then print each line in the file

filename = raw_input('Enter the file name:')
file_content=open(filename,'r')
for line in file_content:
    print line,
line.close()

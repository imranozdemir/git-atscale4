#git-atscale4

# loop through all files in current directory
for file in *
do

# check if it is a file
if [ -f $file ]
then

if [ -x $file ]
then

# print the complete file name with -l option
ls -l $file >> executable.txt

# closing second if statement
fi

# closing first if statement
fi

done

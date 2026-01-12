pwd – Print Working Directory

ls – List files and directories 
ls -l        # long listing with permissions
ls -a        # includes hidden files
ls -lh       # human-readable size

cd – Change directory Moves between directories.
cd /var/log
cd ..
cd ~

mkdir – Create directory reates a new directory.
mkdir testdir
mkdir -p parent/child

rmdir – Remove empty directory 
Deletes an empty directory.
rmdir testdir

touch – Create empty file
Creates a new empty file or updates timestamp.

cp – Copy files or directories
Copies files from one location to another.
cp file1.txt file2.txt
cp -r dir1 dir2

mv – Move or rename files
Moves or renames files or directories.
mv old.txt new.txt
mv file.txt /tmp/

cat – Display file content
Displays the content of a file.
cat file.txt


less – View file page by page
Used to read large files.

head – View beginning of file
Displays first 10 lines by default.
head file.txt
head -n 5 file.txt

chmod – Change permissions
Modifies file permissions.

chown – Change ownership
Changes file owner and group.

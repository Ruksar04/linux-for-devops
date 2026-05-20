# Survival Skills

## Navigation
# Print current directory
pwd

# List all files including hidden with permissions
ls -la

# Change directory
cd foldername

# Go back one level
cd ..

# Go to home directory from anywhere
cd ~

## File Operations
# Create empty file
touch filename.txt

# View file contents
cat filename.txt

# View last N lines of file
tail -n 20 filename.txt

# Watch file live in real time
tail -f filename.txt

# Copy file
cp file.txt destination/

# Move file
mv file.txt destination/

# Rename file
mv oldname.txt newname.txt

# Delete file
rm filename.txt

# Delete folder and everything inside
rm -rf foldername/

# Create folder
mkdir foldername

## Searching
# Find file by name
find . -name "filename.txt"

# Search inside file
grep "pattern" filename.txt

# Search recursively in all files
grep -r "pattern" /var/log/

## Disk and Memory
# Check disk space
df -h

# Check folder size
du -sh foldername/

# Check RAM usage
free -h

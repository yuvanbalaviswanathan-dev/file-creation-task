# File Creation Task

## Commands Used

mkdir my_folder

cd my_folder

echo "Hello from my_file" > my_file.txt

echo "Hello from another_file" > another_file.txt

cat another_file.txt >> my_file.txt

cat my_file.txt

ls

for i in $(seq 1 20); do touch file$i.txt; done

mv file1.txt file1.yml
mv file2.txt file2.yml
mv file3.txt file3.yml
mv file4.txt file4.yml
mv file5.txt file5.yml

ls -lt | head -5# file-creation-task

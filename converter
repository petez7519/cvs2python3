import csv
import json

# Open the CSV file and read its contents
csv_file = 'your_file.csv'
json_file = 'output_file.json'

data = []
with open(csv_file, mode='r') as file:
    reader = csv.DictReader(file)
    for row in reader:
        data.append(row)

# Write to a JSON file
with open(json_file, mode='w') as file:
    json.dump(data, file, indent=4)

print(f"CSV successfully converted to JSON and saved as {json_file}")

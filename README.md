employees = [
    {"id": 101, "name": "Lakshma", "department": "DevOps"},
    {"id": 102, "name": "Rahul", "department": "Testing"},
    {"id": 103, "name": "Anitha", "department": "Development"}
]

print("Employee Details")
print("----------------")

for emp in employees:
    print(f"ID: {emp['id']}")
    print(f"Name: {emp['name']}")
    print(f"Department: {emp['department']}")
    print()

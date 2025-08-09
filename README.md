## Code Explanation (by sections)

### 1. Exercise – Variables

whatexcerisedo = "yoga"
gymname = "gym"

## 2. Breakfast – Tuples
# Tuples are used for fixed sets of food items. Tuples are immutable.
breakfast = ("idly", "chapti", "sambar", "chetani")
carrierbox = ("snacks", "food", "sweet", "tigfien")

## Travel – Lists (Nested)
fromstation = "indiranagar"
tostation = "mg road"
price = 40

metro = [[1, 2, 3], [1, 2, 3], [1, 2, 3]]
print(metro[0])
metro[0].append(4)
metro[2].append(7)
metro[0].remove(2)
print(metro)

## 4. Office Space – Dictionaries
# Dictionaries store key-value pairs (name → role). You can update values using direct assignment or .update().
officecabs = { "dennis": "sde2", "laxman": "sde3" }
officecabs["dennis"] = "sde3"
officecabs.update({"venkatesh": "sde3"})
print(officecabs)

## 5. Actual Work – Nested Dictionaries & Lists
# The company dictionary contains a list of employee-task mappings
# Demonstrates accessing nested structures and looping through them
company = {
    "usa bank": [
        {"dennis": ["ticket1", "ticket2"]},
        {"venakt": "tocket4"},
        {"laxmi": "ticket5"}
    ]
}

print(company["usa bank"])
print(company["usa bank"][1]["venakt"])

for i in company.values():
    for j in i:
        print("employees \n", j)


# 6. Reusability – Functions

# Functions are used to reuse code. These simulate modular parts of the day.

def excerise():
    whatexcerisedo = "yoga"
    gymname = "gym"

def officespace():
    officecabs = { "dennis": "sde2", "laxman": "sde3" }
    officecabs["dennis"] = "sde3"
    officecabs.update({"venkatesh": "sde3"})
    print(officecabs)









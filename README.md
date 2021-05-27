# Python Gradebook

Python Gradebook is a project that lists the marks of the subjects by deriving it from the code
## Installation

Install python from the official website(https://www.python.org/downloads/) and use a text editor like VSCode (https://www.code.visualstudio.com)

```bash
pip install foobar
```

## Code
last_semester_gradebook = [("politics", 80), ("latin", 96), ("dance", 97), ("architecture", 65)]
subjects = ['physics', 'calculus', 'poetry', 'history']
grades = [98, 97, 85, 88]
subjects.append("computer science")
grades.append(100)
gradebook = list(zip(subjects, grades))
print(list(gradebook))
gradebook.append(['visual arts', 93])
full_gradebook = gradebook + last_semester_gradebook
print(full_gradebook)
```

## Contributing
I would greatly appreciate contributions. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate. Show some love by starring the repository

## License
[MIT](https://choosealicense.com/licenses/mit/)

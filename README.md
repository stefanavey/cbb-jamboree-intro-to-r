# CBB Jamboree - Intro to R (DataCamp Course)
<a href=https://www.datacamp.com//teach/repositories/68830271/go target="_blank"><img src="https://s3.amazonaws.com/assets.datacamp.com/img/github/content-engineering-repos/course_button.png" width="150"></a>
<a href=https://www.datacamp.com//teach/repositories target="_blank"><img src="https://s3.amazonaws.com/assets.datacamp.com/img/github/content-engineering-repos/dashboard_button.png" width="150"></a>

## Workflow

1. Edit the markdown and yml files in this repository.
2. Check out your build attempts on the <a href=https://www.datacamp.com//teach/repositories target="_blank">Teach Dashboard</a>.
3. Check out your automatically updated <a href=https://www.datacamp.com/teach/repositories/68830271/go target="_blank">Course on DataCamp</a>

## Getting Started

A DataCamp course consists of two types of files:

- `course.yml`, a <a href=http://docs.ansible.com/ansible/YAMLSyntax.html target="_blank">YAML-formatted file</a> that contains course metadata (title, description, instructors, etc.)
- `chapterX.md`, a markdown file with:
   - a YAML header containing chapter information.
   - markdown chunks representing DataCamp Exercises.

Every DataCamp exercise consists of different parts, read up about them <a href=https://www.datacamp.com//teach/documentation#tab_code_exercises target="_blank">here</a>. A very important part about DataCamp exercises is to provide automated personalized feedback to students. In R, these so-called Submission Correctness Tests (SCTs) are written with the <a href=https://github.com/datacamp/testwhat target="_blank">`testwhat`</a> package. SCTs for Python exercises are coded up with <a href=https://github.com/datacamp/pythonwhat target="_blank">`pythonwhat`</a>. Check out the GitHub repositories' wiki pages for more information and examples.

Want to learn more? Check out the <a href=https://www.datacamp.com//teach/documentation target="_blank">documentation</a> on teaching at DataCamp.

*Happy teaching!*

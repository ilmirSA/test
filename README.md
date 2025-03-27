```python
def get_courses_list(courses_url):
    html = fetch_html(courses_url)
    if html:
        # .... parsing logic
        return courses_list
    else:
        print("cant load list of courses")
        exit()

```

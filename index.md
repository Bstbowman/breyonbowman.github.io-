---
layout: default
---

Text can be **bold**, _italic_, or ~~strikethrough~~.

[Link to another page](./https://www.linkedin.com/in/breyon-bowman-729391237/).

There should be whitespace between paragraphs.

There should be whitespace between paragraphs. We recommend including a README, or a file with information about your project. 

# About me

Experienced cybersecurity enthusiast with a strong foundation in network security, incident response, and vulnerability management whose journey in computer science has led me to develop a passion for cybersecurity, and I am now agar to start my professional cybersecurity career, specifically aiming to join pursue my long term goal to being a pen tester.


### Projects

<h2 style="text-align: center;">Projects</h2>


<details>
<summary>
  <span class="projects-title" style="transition: font-size 0.3s ease;">Projects</span>
</summary>

<style>
.projects-title:hover {
  font-size: 150%;
}

.project-bubble {
  display: inline-block;
  background-color: black;
  color: white;
  padding: 10px;
  border-radius: 20px;
  margin: 10px;  /* Increased from 5px to 10px */
  cursor: pointer;
  transition: all 0.3s ease;
}

.project-bubble:hover {
  transform: scale(1.1);
}

.associated-project {
  display: none;
  background-color: #444;
  color: white;
  padding: 5px;
  border-radius: 10px;
  font-size: 0.8em;
  margin-top: 5px;
}

.project-bubble:hover .associated-project {
  display: block;
  animation: popIn 0.3s ease-out;
}

@keyframes popIn {
  0% { transform: scale(0); }
  80% { transform: scale(1.1); }
  100% { transform: scale(1); }
}

.project-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 20px;  /* Added gap property to increase spacing between bubbles */
}

.project-bubble:nth-child(odd) {
  transform: translateY(-10px);
}

.project-bubble:nth-child(even) {
  transform: translateY(10px);
}

.project-bubble:hover {
  transform: scale(1.1) translateY(0);
}
</style>

<div class="project-container">
  <div class="project-bubble">
    Updating a File Using Python
    <div class="associated-project">
      <a href="https://docs.google.com/presentation/d/104vj63hCLHkrugQQTfK1Dd7oiMhas2HH2_lNUsSmCNk/edit#slide=id.p">Updating a File Using Python lab</a>
    </div>
  </div>

  <div class="project-bubble">
    Document an incident with an incident handler's journal
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1zzNWQI49lH9ITrDKudjlw4stTf1I7yuZCtP2FJTDzK0/edit?resourcekey=0-zsGjrRjrrO7KNZuAUyZMOg">Incident handler's journal example</a>
    </div>
  </div>

  <div class="project-bubble">
    Vulnerability assessment report
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1AsN7zZNlcRHzRmOQk43vi8Z-uJ_TSroLbJ_ci9qFQIo/edit?resourcekey=0-wFIjLbfogxxC3RqkiK02Wg">Vulnerability assessment report lab</a>
    </div>
  </div>

  <div class="project-bubble">
    Incident response execution
    <div class="associated-project">
      <a href="https://docs.google.com/presentation/d/1BoN-haIWpvA5R5iYkNsq2a7nGKuK5lOv4adJcEHwMEE/edit#slide=id.g279c45888cd_0_36">Use the NIST Cybersecurity Framework to respond to a security incident lab</a>
    </div>
  </div>

  <div class="project-bubble">
    Use Linux commands to manage file permissions
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1BCXBdrraCHh7w3FrnfMvs-FiOzDjWzsWIlFiUcTBME8/edit?resourcekey=0--jfRjUAXgWP7VlQLR32liw">File permissions in Linux lab</a>
    </div>
  </div>

  <div class="project-bubble">
    Conduct a security audit
    <div class="associated-project">
      <a href="https://docs.google.com/document/d/1yi9OqjPmkz0-nPTWne3W0Jqnzct7HHyOgSKWU_dvSyA/edit">Controls and compliance checklist lab</a>
    </div>
  </div>
</div>

</details>
#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

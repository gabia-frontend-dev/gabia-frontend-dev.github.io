## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/gabia-frontend-dev/gabia-frontend-dev.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### # HTML 설정하기

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
<!DOCTYPE html>
<html>
<head>
<!--Import gtris.css-->
<link type="text/css" rel="stylesheet" href="https://static.gabia.com/gtris/1.2.0/css/gtris.min.css">
</head>
<body>
<!--Import jQuery before gtris.js-->
<script type="text/javascript" src="https://static.gabia.com/libs/jquery/1.9.1/jquery.min.js"></script>
<script type="text/javascript" src="https://static.gabia.com/gtris/1.2.0/js/gtris.min.js"></script>
</body>
</html>
```

### # 기본 모달 마크업

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
<div id="id-modal" class="gt-modal">
  <div class="gt-modal-content gt-animate-opacity">
    <div class="gt-modal-header"></div>
      <div class="gt-modal-body"></div>
      <div data-modal="hide" class="gt-modal-close">
        <a href="javascript:void(0);">
          <img src="http://static.gabia.com/gtris/1.1.0/assets/images/delete.svg" alt="닫기">
        </a>
    </div>
  </div>
</div>
```

### # 기본 모달 마크업

```javascript
$('button').click(function(event) {
  gtris.ui.modal.open({
    target: 'Set the URL, ID or Class.'
  })
});
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/gabia-frontend-dev/gabia-frontend-dev.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.



<script\>... alert('ddddd') ...</script\>

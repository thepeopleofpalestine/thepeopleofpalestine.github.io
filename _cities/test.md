---
name: Test 
location:
    x: 150
    y: 150
synopsis: |
    This is a test city. Delete it when you're ready.
cover: /assets/images/cover.jpg
gallery:
    - src: /assets/images/cover.jpg
      title: "1 This is some caption about things."
      h: 2698
      w: 4039
    - src: /assets/images/cover.jpg
      title: "2 This is some caption about things."
      h: 2698
      w: 4039
    - src: /assets/images/cover.jpg
      title: "3 This is some caption about things."
      h: 2698
      w: 4039
    - src: /assets/images/cover.jpg
      title: "4 This is some caption about things."
      h: 2698
      w: 4039
---

# Demo of image lightboxing (replace thumbnail with a smaller version of the image):

{% include lightbox.html thumbnail="/assets/images/sm-cover.jpg" src="/assets/images/cover.jpg" caption="Some caption" height=2698 width=4039 %}

You can just not include a `thumbnail` and it will just show the large image.

{% include lightbox.html src="/assets/images/cover.jpg" caption="Some caption" height=2698 width=4039 %}

You can use `text` instead of thumbnail or nothing to make the lightbox a text link. Very important to note this is different than `caption`.

{% include lightbox.html text="blah blah blah" src="/assets/images/cover.jpg" caption="Some caption" height=2698 width=4039 %}

# Demo of Case Study:

{% include lightbox.html thumbnail="/assets/cities/hebron/sm-southafrica.jpg" src="/assets/cities/hebron/southafrica.jpg" caption="Pass Laws" height=1200 width=1700 %}

End of Demo

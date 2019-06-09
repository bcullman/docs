{%- assign pageroot = "" -%}
{%- assign pathArray = page.path | split: '/' -%}
{%- for i in (2..pathArray.size) -%}
    {%- assign pageroot = pageroot | append: "../" -%}
{%- endfor -%}

---
layout: default
title: 개요
nav_order: 1
description: "Just the Docs is a responsive Jekyll theme with built-in search that is easily customizable and hosted on GitHub Pages."
permalink: /
---

# 개요
{: .fs-9 }

클라우드 설정 미흡으로 인한 데이터 유출 사고가 점점 증가하고 있습니다. 이에 D-CLO는 300개의 탐지 룰셋을 통해 클라우드 설정에 대한 취약점을 점검하고 점검 결과를 모니터링하여 클라우드 설정 미흡으로 인한 피해를 사전에 방지할 수 있는 솔루션입니다.
{: .fs-6 .fw-300 }

<!-- [Get started now](#getting-started){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
[View it on GitHub][Just the Docs repo]{: .btn .fs-5 .mb-4 .mb-md-0 } -->

---

## 제품 특징

D-CLO는 다음과 같은 특징이 있습니다.

| 분류                      | 주요 기능                      | 설명                                         |
|:--------------------------|:--------------------------------|:--------------------------------------------|
| 멀티 클라우드 지원        | AWS 클라우드 취약점 진단      | AWS 클라우드 내 취약한 설정 확인 및 모니터링 가능   |
|                           | NCP 클라우드 취약점 진단      | NCP(네이버) 클라우드 내 취약한 설정 확인 및 모니터링 가능 |
|                           | GCP 클라우드 취약점 진단      | GCP(구글) 클라우드 내 취약한 설정 확인 및 모니터링 가능 |
|                           | AZURE 클라우드 취약점 진단   | AZURE(MS) 클라우드 내 취약한 설정 확인 및 모니터링 가능 |
| 지속적인 모니터링         | 대시보드를 통한 모니터링      | 진단 결과를 대시보드를 통한 모니터링이 수월        |
| 보고서 리포팅             | 엑셀 보고서 출력              | 결과를 엑셀 보고서로 출력하여 문서 관리 및 증적 사용 가능 |
|                           | 워드 보고서 출력              | 결과를 워드 보고서로 출력하여 문서 관리 및 증적 사용 가능 |
| 클라우드 리소스 시각화    | IAM 리소스 시각화             | 비가시성인 IAM 리소스를 시각화하여 사용자 및 정책 관리  |
|                           | 클라우드 리소스 시각화        | 비가시성인 클라우드 리소스를 시각화하여 모니터링 관리   |

---

## 호환 브라우저

D-CLO 호환 브라우저는 아래의 표와 같습니다. 모든 브라우저에서 동작하지만, 표기된 브라우저에 최적화 되어있기 때문에 아래에 브라우저를 사용할 것을 권장 드립니다.

| 브라우저 명       | 사용 가능 여부 | 비고 |
|:-----------------|:--------------|:----|
| Microsoft Edge   | O             |     |
| Chrome           | O             |     |
| Firefox          | O             |     |
| Naver whale      | O             |     |

※ 이 가이드에선 구글(Google) 크롬(Chrome)을 기준으로 설명합니다.


<!-- 
{: .warning }
> This website documents the features of the current `main` branch of the Just the Docs theme. See [the CHANGELOG]({% link CHANGELOG.md %}) for a list of releases, new features, and bug fixes.

Just the Docs is a theme for generating static websites with [Jekyll]. You can write source files for your web pages using [Markdown], the [Liquid] templating language, and HTML.[^1] Jekyll builds your site by converting all files that have [front matter] to HTML. Your [Jekyll configuration] file determines which theme to use, and sets general parameters for your site, such as the URL of its home page.

Jekyll builds this Just the Docs theme docs website using the theme itself. These web pages show how your web pages will look *by default* when you use this theme. But you can easily *[customize]* the theme to make them look completely different!

Browse the docs to learn more about how to use this theme.

## Getting started

The [Just the Docs Template] provides the simplest, quickest, and easiest way to create a new website that uses the Just the Docs theme. To get started with creating a site, just click "[use the template]"!

{: .note }
To use the theme, you do ***not*** need to clone or fork the [Just the Docs repo]! You should do that only if you intend to browse the theme docs locally, contribute to the development of the theme, or develop a new theme based on Just the Docs.

You can easily set the site created by the template to be published on [GitHub Pages] – the [template README] file explains how to do that, along with other details.

If [Jekyll] is installed on your computer, you can also build and preview the created site *locally*. This lets you test changes before committing them, and avoids waiting for GitHub Pages.[^2] And you will be able to deploy your local build to a different platform than GitHub Pages.

More specifically, the created site:

- uses a gem-based approach, i.e. uses a `Gemfile` and loads the `just-the-docs` gem
- uses the [GitHub Pages / Actions workflow] to build and publish the site on GitHub Pages

Other than that, you're free to customize sites that you create with the template, however you like. You can easily change the versions of `just-the-docs` and Jekyll it uses, as well as adding further plugins.

{: .note }
See the theme [README][Just the Docs README] for how to use the theme as a gem without creating a new site.

## About the project

Just the Docs is &copy; 2017-{{ "now" | date: "%Y" }} by [Patrick Marsceill](https://patrickmarsceill.com).

### License

Just the Docs is distributed by an [MIT license](https://github.com/just-the-docs/just-the-docs/tree/main/LICENSE.txt).

### Contributing

When contributing to this repository, please first discuss the change you wish to make via issue,
email, or any other method with the owners of this repository before making a change. Read more about becoming a contributor in [our GitHub repo](https://github.com/just-the-docs/just-the-docs#contributing).

#### Thank you to the contributors of Just the Docs!

<ul class="list-style-none">
{% for contributor in site.github.contributors %}
  <li class="d-inline-block mr-1">
     <a href="{{ contributor.html_url }}"><img src="{{ contributor.avatar_url }}" width="32" height="32" alt="{{ contributor.login }}"></a>
  </li>
{% endfor %}
</ul>

### Code of Conduct

Just the Docs is committed to fostering a welcoming community.

[View our Code of Conduct](https://github.com/just-the-docs/just-the-docs/tree/main/CODE_OF_CONDUCT.md) on our GitHub repository.

----

[^1]: The [source file for this page] uses all three markup languages.

[^2]: [It can take up to 10 minutes for changes to your site to publish after you push the changes to GitHub](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll#creating-your-site).

[Jekyll]: https://jekyllrb.com
[Markdown]: https://daringfireball.net/projects/markdown/

[Liquid]: https://github.com/Shopify/liquid/wiki
[Front matter]: https://jekyllrb.com/docs/front-matter/
[Jekyll configuration]: https://jekyllrb.com/docs/configuration/
[source file for this page]: https://github.com/just-the-docs/just-the-docs/blob/main/index.md
[Just the Docs Template]: https://just-the-docs.github.io/just-the-docs-template/
[Just the Docs]: https://just-the-docs.com
[Just the Docs repo]: https://github.com/just-the-docs/just-the-docs
[Just the Docs README]: https://github.com/just-the-docs/just-the-docs/blob/main/README.md
[GitHub Pages]: https://pages.github.com/
[Template README]: https://github.com/just-the-docs/just-the-docs-template/blob/main/README.md
[GitHub Pages / Actions workflow]: https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/
[customize]: {% link docs/customization.md %}
[use the template]: https://github.com/just-the-docs/just-the-docs-template/generate -->

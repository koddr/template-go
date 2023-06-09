# {{PROJECT}}

[![Go version][go_version_img]][go_dev_url]
[![Go report][go_report_img]][go_report_url]
[![Code coverage][go_code_coverage_img]][repo_url]
[![Wiki][repo_wiki_img]][repo_wiki_url]
[![License][repo_license_img]][repo_license_url]

**{{PROJECT}}** description ...

Features:

- 100% **free** and **open source**.
- ...
- ...

## ⚡️ Quick start

First, [download][go_download_url] and install **Go**. Version `1.20` (or 
higher) is required.

Installation is done by using the [`go install`][go_install_url] command:

```console
go install github.com/koddr/{{PROJECT}}@latest
```

> 💡 Note: See the repository's [Release page][repo_releases_url], if you want
> to download a ready-made `deb`, `rpm`, `apk` or `Arch Linux` package.

Also, GNU/Linux and macOS users available way to install via 
[Homebrew][brew_url]:

```console
# Tap a new formula:
brew tap koddr/tap

# Installation:
brew install koddr/tap/{{PROJECT}}
```

Prepare your data:

- ...
- ...

> 💡 Note: See the repository's [Wiki][repo_wiki_url] page to understand the 
> structure of the file.

Next, run `{{PROJECT}}` with (_or without_) options:

```console
{{PROJECT}} -p ./path/to/file
```

Done! 🎉 Your tasks have been executed.

### 🐳 Docker-way to quick start

If you don't want to physically install `{{PROJECT}}` to your system, you feel
free to using our [official Docker image][docker_image_url] and run it from
isolated container:

```console
docker run --rm -it -v ${PWD}:${PWD} -w ${PWD} koddr/{{PROJECT}}:latest [COMMANDS]
```

## ✨ Usage

Basic usage and full code examples of all functions of the `{{PROJECT}}` 
package, you can find on the [pkg.go.dev][go_dev_url] page.

## 🧩 Options

| Option | Description          | Is required? | Type     | Default value |
|--------|----------------------|--------------|----------|---------------|
| `-p`   | set a path to a file | yes          | `string` | `./file.json` |

## ✨ Solving case

...

## 💡 Motivation

...

## 🏆 A win-win cooperation

And now, I invite you to participate in this project! Let's work **together** to
create the **most useful** tool for developers on the web today.

- [Issues][repo_issues_url]: ask questions and submit your features.
- [Pull requests][repo_pull_request_url]: send your improvements to the current.

Your PRs & issues are welcome! Thank you 😘

## ⚠️ License

[`{{PROJECT}}`][repo_url] is free and open-source software licensed 
under the [Apache 2.0 License][repo_license_url], created and supported with 🩵 
for people and robots by [Vic Shóstak][author_url].

<!-- Go links -->

[go_download_url]: https://golang.org/dl/
[go_install_url]: https://golang.org/cmd/go/#hdr-Compile_and_install_packages_and_dependencies
[go_report_url]: https://goreportcard.com/report/github.com/koddr/{{PROJECT}}
[go_dev_url]: https://pkg.go.dev/github.com/koddr/{{PROJECT}}

[go_version_img]: https://img.shields.io/badge/Go-1.20+-00ADD8?style=for-the-badge&logo=go
[go_code_coverage_img]: https://img.shields.io/badge/code_coverage-0%25-success?style=for-the-badge&logo=none
[go_report_img]: https://img.shields.io/badge/Go_report-A+-success?style=for-the-badge&logo=none

<!-- Repository links -->

[repo_url]: https://github.com/koddr/{{PROJECT}}
[repo_issues_url]: https://github.com/koddr/{{PROJECT}}/issues
[repo_pull_request_url]: https://github.com/koddr/{{PROJECT}}/pulls
[repo_releases_url]: https://github.com/koddr/{{PROJECT}}/releases
[repo_wiki_url]: https://github.com/koddr/{{PROJECT}}/wiki
[repo_license_url]: https://github.com/koddr/{{PROJECT}}/blob/main/LICENSE

[repo_wiki_img]: https://img.shields.io/badge/docs-wiki_page-blue?style=for-the-badge&logo=none
[repo_license_img]: https://img.shields.io/badge/license-Apache_2.0-red?style=for-the-badge&logo=none

<!-- Author links -->

[author_url]: https://github.com/koddr

<!-- Readme links -->

[docker_image_url]: https://hub.docker.com/repository/docker/koddr/{{PROJECT}}
[brew_url]: https://brew.sh

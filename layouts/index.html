{{ define "main" }}
{{- partial "jumbotron.html" . -}}
<div class="download">
    {{- with .Site.Params.homeDownload  | markdownify }}
    <p>{{.}}</p>
    {{- end }}
</div>
<div class="container py-3" id="posts">
    <div class="row justify-content-center">
        {{ $pages := where site.RegularPages "Type" "in" site.Params.mainSections }}
       {{ range (.Paginate $pages).Pages }}
        <div class="col-lg-6 col-md-6 pt-2">
            <div class="card h-100">
                <div class="card-body bg-transparent p-3 shadow-sm">
                    <a href="{{ .RelPermalink }}" class="primary-font card-title">
                        <h2 class="card-title bg-transparent fw-bold" title="{{ .Title }}">{{ .Title }}</h2>
                    </a>
                    <div class="card-text ">
                        <p>{{ .Summary | truncate 200}}</p>
                    </div>
                </div>
                <div class="mt-auto card-footer">
                    <span class="float-start ">{{ .Date.Format "January 2, 2006" }}</span>
                    <a href="{{ .RelPermalink }}" class="float-end btn btn-outline-indigo btn-sm">Read</a>
                </div>
            </div>
        </div>
    {{ end }}
</div>
<br>
{{- partial "paginator.html" . -}}

{{ end }}

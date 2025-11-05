#### Redocly Installation

npm install redoc

npm install -g @redocly/cli

dir "$(npm prefix -g)\node_modules\@redocly\cli\bin"

$env:Path += ";$(npm prefix -g)\"

### Redocly Configuration
Setup in redocly.yaml

    apis:
      sample@v1:
        root: <file.yaml>

### Test YAML
redocly lint

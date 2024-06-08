FROM githubchangeloggenerator/github-changelog-generator:1.16.2

# Install bash.
RUN apk add --no-cache bash

COPY entrypoint.sh /entrypoint.sh
RUN chmod +x ./.github/scripts/entrypoint.sh
ENTRYPOINT ["./.github/scripts/entrypoint.sh"]

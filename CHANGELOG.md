![image](https://i.imgur.com/ydnAi5N.png)
CHANGELOG_CONTENT=$(head -n 1 CHANGELOG.md)
    echo "::set-output name=content::$CHANGELOG_CONTENT"
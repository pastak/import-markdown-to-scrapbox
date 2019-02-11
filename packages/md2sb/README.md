# md2sb

Encode Markdown to Scrapbox.io style text

## Sample Result

[Sample Text(Ja)](test/fixtures/md/sample-ja.md) to https://scrapbox.io/pastak-pub/md2sb%20Sample

(This sample text is from http://qiita.com/salchu/items/da81122ed50b35feda4d ([Revision](http://qiita.com/salchu/items/da81122ed50b35feda4d/revisions/6)))

## Usage

### CLI

- `% npx md2sb hoge.md > hoge.txt`
  - You can pass filename as option
- `% cat hoge.md | md2sb > hoge.txt`
  - You can pass markdown text via stdin

### API

TBW

## Development

- Require
  - NodeJS

1. Fork it
2. `% git clone git@github.com:YOUR-NAME/md2sb.git`
3. `cd md2sb`
4. `git checkout -b YOUR_WORKING_BRANCH`
5. Write Some Code!
  - Build: `% npm run build`
    - Watch: `% npm run watch`
  - Test: `% npm test`
    - Test Watching: `% npm test:watch`
6. Commit your work
7. Open PR to this repository 🎉

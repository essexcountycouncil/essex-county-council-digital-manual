1.  [Contents](/docs/core/design/overview)
2.  [Table](#)

# Table

Use a table to make it easier for users to compare and scan information.

## Example

<div class="table">
  <table>
    <caption>2018 care charges</caption>
      <thead>
        <tr>
          <th scope="col">Type of service</th>
          <th scope="col">Frequency</th>
          <th scope="col">Cost</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Home Support Services (normal hours) one-to-one</td>
          <td>Hourly</td>
          <td>£17.04</td>
        </tr>
        <tr>
          <td>Day Care</td>
          <td>Per session</td>
          <td>£10.73</td>
        </tr>
        <tr>
          <td>Day Care with transport</td>
          <td>Per session</td>
          <td>£12.20</td>
        </tr>
      </tbody>
  </table>
</div>

    <table>
      <caption>2018 care charges</caption>
        <thead>
          <tr>
            <th scope="col">Type of service</th>
            <th scope="col">Frequency</th>
            <th scope="col">Cost</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Home Support Services (normal hours) one-to-one</td>
            <td>Hourly</td>
            <td>£17.04</td>
          </tr>
          <tr>
            <td>Day Care</td>
            <td>Per session</td>
            <td>£10.73</td>
          </tr>
          <tr>
            <td>Day Care with transport</td>
            <td>Per session</td>
            <td>£12.20</td>
          </tr>
        </tbody>
    </table>

## When to use a table

Use a table to let users compare information in rows and columns.

## When not to use a table

Do not use a table to layout content on a page. Instead, use the [grid system](/docs/core/grid-system).

## How tables work
### Accessibility

Follow [WebAIM's guidance for tables](https://webaim.org/techniques/tables/data) and

- give tables captions
- use the scope attribute to associate the data cells with the appropriate headers
- let the browser window determine the width of the table whenever possible, to reduce horizontal scrolling

### Table captions

Use the `<caption>` element to decribe a table in the same way you would use a heading. A caption helps users find, navigate and understand tables.

### Table headers

Use table headers to tell users what the rows and columns represent. The scope atribute helps associate data with the appropriate header.
Screen readers would read out the last row as: "Type of service: Daycare with transport. Frequency: Per session. Cost: £12.20".

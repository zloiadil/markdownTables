<table border="1" cellspacing="0" cellpadding="5">
  <thead>
    <tr>
      <th>Path</th>
      <th>Change id</th>
      <th>Comment</th>
      <th>ER</th>
      <th>Link</th>
      <th>Example</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><code>paths.[*].[*].parameters.[*]. examples</code></td>
      <td><code>add-examples-object-for-parameter</code></td>
      <td></td>
      <td><code>annotation</code></td>
      <td><code>add-examples-object-for-parameter</code></td>
      <td>
        <details>
          <summary>before</summary>
          <pre><code class="language-yaml">
openapi: 3.0.0
...
paths:
  /pets:
    post:
      parameters:
        - name: filter
          in: query
          schema:
            type: string
          </code></pre>
        </details>
        <br>
        <details>
          <summary>after</summary>
          <pre><code class="language-yaml">
openapi: 3.0.0
...
paths:
  /pets:
    post:
      parameters:
        - name: filter
          in: query
          schema:
            type: string
        examples:
          example1:
            value: name
          </code></pre>
        </details>
      </td>
    </tr>
    <!-- Следующая строка, идентичная предыдущей -->
    <tr>
      <td><code>paths.[*].[*].parameters.[*]. examples</code></td>
      <td><code>add-examples-object-for-parameter</code></td>
      <td></td>
      <td><code>annotation</code></td>
      <td><code>add-examples-object-for-parameter</code></td>
      <td>
        <details>
          <summary>before</summary>
          <pre><code class="language-yaml">
openapi: 3.0.0
...
paths:
  /pets:
    post:
      parameters:
        - name: filter
          in: query
          schema:
            type: string
          </code></pre>
        </details>
        <br>
        <details>
          <summary>after</summary>
          <pre><code class="language-yaml">
openapi: 3.0.0
...
paths:
  /pets:
    post:
      parameters:
        - name: filter
          in: query
          schema:
            type: string
        examples:
          example1:
            value: name
          </code></pre>
        </details>
      </td>
    </tr>
  </tbody>
</table>

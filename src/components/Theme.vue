<template>
  <div class="theme" id="themes">
    <h2 class="slogan">Themes😛</h2>
    <div class="theme-table"
    :class="{'cadmium' : changeTheme === 0 ,'graphite': changeTheme === 1, 'ulysses' : changeTheme === 2, 'dark-theme' : changeTheme === 3, 'material' : changeTheme === 4, 'one-dark' : changeTheme === 5}"
    >
      <h3>Themes</h3>
      <table>
        <thead>
          <tr>
            <th>Name</th>
            <th>Use for</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Mark Text</td>
            <td>Write markdown</td>
          </tr>
        </tbody>
      </table>
      <code>// Yeh, Mark Text is simple and elegant markdown editor.<br>
          <span style="color: #07a">const</span> marktext = 'markdown editor'
      </code>
      <blockquote>
        It has roots in a piece of classical Latin literature from 45 BC
making it over 2000 years old.
      </blockquote>
    </div>
    <div class="themes-option">
      <div class="light">
        <h2>Light Themes</h2>
        <div class="option">
          <div class="inline option-one">
            <input type="radio" name="theme" id="one-l" checked @click="changeTheme = 0">
            <label for="one-l">Cadmium light</label>
          </div>
          <div class="inline option-two">
            <input type="radio" name="theme" id="two-l" @click="changeTheme = 1">
            <label for="two-l">Graphite light</label>
          </div>
          <div class="inline option-three">
            <input type="radio" name="theme" id="three-l" @click="changeTheme = 2">
            <label for="three-l">Ulysses light</label>
          </div>
        </div>
      </div>
      <div class="dark">
        <h2>Dark Themes</h2>
        <div class="option">
          <div class="inline option-one">
            <input type="radio" name="theme" id="one-d" @click="changeTheme = 3">
            <label for="one-d">Dark</label>
          </div>
          <div class="inline option-two">
            <input type="radio" name="theme" id="two-d" @click="changeTheme = 4">
            <label for="two-d">Material Dark</label>
          </div>
          <div class="inline option-three">
            <input type="radio" name="theme" id="three-d" @click="changeTheme = 5">
            <label for="three-d">One Dark</label>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Theme',
  data () {
    return {
      changeTheme: null
    }
  }
}
</script>

<style>
    .theme {
        background-color:#E9F9F9 !important;
        position: relative;
        height: 100vh;
        width: 100%;
        position: relative;
        background-size: 250px 250px;
        background-position: 73% 20%;
        background-image: url('data:image/svg+xml;base64,DQo8c3ZnIGlkPSJMYXllcl8xIiBkYXRhLW5hbWU9IkxheWVyIDEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHdpZHRoPSI2ODYuMiIgaGVpZ2h0PSI1OTIuMTYiIHZpZXdCb3g9IjAgMCA2ODYuMiA1OTIuMTYiPg0KICA8ZGVmcz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudCIgeDE9IjI4MS4xMyIgeTE9IjY4OS45MyIgeDI9IjExMC41IiB5Mj0iOTg0LjczIiBncmFkaWVudFRyYW5zZm9ybT0idHJhbnNsYXRlKDAgLTE3NCkiIGdyYWRpZW50VW5pdHM9InVzZXJTcGFjZU9uVXNlIj4NCiAgICAgIDxzdG9wIG9mZnNldD0iMCIgc3RvcC1vcGFjaXR5PSIwIi8+DQogICAgICA8c3RvcCBvZmZzZXQ9IjAuOTgiLz4NCiAgICA8L2xpbmVhckdyYWRpZW50Pg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTIiIHgxPSIxNjEuNDMiIHkxPSIyNDYuOTUiIHgyPSIxOTUuOSIgeTI9Ii0xOTAuNjkiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIC02OC45LCA0MTkuNDkpIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMyIgeDE9IjM0OS4yIiB5MT0iMTkyLjU0IiB4Mj0iMjM5Ljg4IiB5Mj0iLTEyNi45MSIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgMCwgNDIwKSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTQiIHgxPSI1NDEuNDgiIHkxPSIyOTMuNTUiIHgyPSI3MDAuNzYiIHkyPSItMTEwLjI3IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEsIDAsIDAsIC0xLCAwLCA0MjApIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNSIgeDE9IjU1NC40NCIgeTE9IjM0Ny40MiIgeDI9IjU4MC40MiIgeTI9Ii04My4wNiIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgMCwgNDIwKSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTYiIHgxPSI1NTIuOSIgeTE9IjM0Ny4zMyIgeDI9IjU3OC44OCIgeTI9Ii04My4xNSIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgMCwgNDIwKSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTciIHgxPSI1NTEuMzYiIHkxPSIzNDcuMjMiIHgyPSI1NzcuMzQiIHkyPSItODMuMjQiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIDAsIDQyMCkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC04IiB4MT0iOTAuMjIiIHkxPSIzMTkuNDEiIHgyPSIxMTYuMiIgeTI9Ii0xMTEuMDciIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIDAsIDQyMCkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC05IiB4MT0iODguNjgiIHkxPSIzMTkuMzEiIHgyPSIxMTQuNjYiIHkyPSItMTExLjE3IiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEsIDAsIDAsIC0xLCAwLCA0MjApIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTAiIHgxPSI4Ny4xNCIgeTE9IjMxOS4yMiIgeDI9IjExMy4xMiIgeTI9Ii0xMTEuMjYiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIDAsIDQyMCkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xMSIgeDE9IjMzNi42MSIgeTE9IjMzNC4yOCIgeDI9IjM2Mi41OCIgeTI9Ii05Ni4yIiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEsIDAsIDAsIC0xLCAwLCA0MjApIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTIiIHgxPSIzMzUuMDciIHkxPSIzMzQuMTgiIHgyPSIzNjEuMDQiIHkyPSItOTYuMyIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgMCwgNDIwKSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTEzIiB4MT0iMzMzLjUzIiB5MT0iMzM0LjA5IiB4Mj0iMzU5LjUiIHkyPSItOTYuMzkiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIDAsIDQyMCkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xNCIgeDE9IjIyMi41MyIgeTE9IjM1OC40OCIgeDI9IjI1OS45OCIgeTI9IjMwOS40OSIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgMCwgNTk0KSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTE1IiB4MT0iMzYwLjI0IiB5MT0iMjA0LjEzIiB4Mj0iMzgzLjg4IiB5Mj0iMjA0LjEzIiBncmFkaWVudFRyYW5zZm9ybT0ibWF0cml4KDEsIDAsIDAsIC0xLCAtNjguOSwgNDE5LjQ5KSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPg0KICAgICAgPHN0b3Agb2Zmc2V0PSIwIiBzdG9wLWNvbG9yPSIjZWNjNGQ3Ii8+DQogICAgICA8c3RvcCBvZmZzZXQ9IjAuNDIiIHN0b3AtY29sb3I9IiNlZmQ0ZDEiLz4NCiAgICAgIDxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iI2YyZWFjOSIvPg0KICAgIDwvbGluZWFyR3JhZGllbnQ+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTYiIHgxPSIyODYuOTUiIHkxPSI1Mi4zNiIgeDI9IjI4Ni42NCIgeTI9Ii0yOC41OSIgZ3JhZGllbnRUcmFuc2Zvcm09Im1hdHJpeCgxLCAwLCAwLCAtMSwgLTY4LjksIDQxOS40OSkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xNyIgeDE9IjUyNDkuNTkiIHkxPSIxNDguMjgiIHgyPSI1Mjc1LjEiIHkyPSIxNDguNzUiIGdyYWRpZW50VHJhbnNmb3JtPSJ0cmFuc2xhdGUoNTQ3My4xMyA0MTkuNDkpIHJvdGF0ZSgxODApIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTE1Ii8+DQogICAgPGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTgiIHgxPSI1MjUxLjA3IiB5MT0iMTUyLjQxIiB4Mj0iNTI0NS44MSIgeTI9IjE0OS42MyIgZ3JhZGllbnRUcmFuc2Zvcm09InRyYW5zbGF0ZSg1NDczLjE0IDQxOS40OSkgcm90YXRlKDE4MCkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtMTUiLz4NCiAgICA8bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xOSIgeDE9IjMxMy43OSIgeTE9IjIwOS4yOSIgeDI9IjMyMy45MiIgeTI9IjIwOS4yOSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC0xNSIvPg0KICAgIDxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTIwIiB4MT0iMjk4LjU3IiB5MT0iMTQzLjQ0IiB4Mj0iNDE3LjM3IiB5Mj0iMzEuMjQiIGdyYWRpZW50VHJhbnNmb3JtPSJtYXRyaXgoMSwgMCwgMCwgLTEsIC02OC45LCA0MTkuNDkpIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+DQogIDwvZGVmcz4NCiAgPHRpdGxlPjkuIHN0aWNraWVzX25vdGVzPC90aXRsZT4NCiAgPHBhdGggZD0iTTE5Mi42NywyMy4wN2MyNS4zMyw2LjQ3LDQ4Ljg5LDIwLjcxLDc1LjE2LDIwLjYyLDI1LjQzLS4wOCw0OC4xNi0xMy41Myw3MS41My0yMi44QzM3My41OCw3LjMxLDQxMS4xLDIuMzQsNDQ4LjI4LjU0LDQ3OC45My0uOTUsNTExLS4wOSw1MzguMjgsMTNzNDYuODIsMzcuNzIsNTcuODksNjQuMzgsMTQuMzEsNTUuNTIsMTUuNTYsODQuMDVjMSwyNC4xNC43NSw0OC41Niw2LjU1LDcyLjEyLDgsMzIuNTMsMjcuMTcsNjEuNTgsNDIuNTMsOTEuNzcsMTIuMjksMjQuMTQsMjIuMzcsNDkuNzMsMjQuODQsNzYuMzVzLTMuMjQsNTQuNTYtMjAuMDgsNzYuMjZDNjQwLjM3LDUxMC40Miw1OTUsNTIzLjg4LDU1Miw1MjcuMzVjLTI0LjExLDEuOTQtNDksMS41LTcxLjU2LDkuNTYtMTUuMjEsNS40Mi0yOC41NywxNC40NS00My4xMSwyMS4yNi0yOSwxMy41OS02MiwxOC4wOS05NC40NSwxOS42NmE1NzcuOTMsNTc3LjkzLDAsMCwxLTI0MS42OS00MC4zNGMtMTEuNDItNC41OC0yMi44Ni05LjY1LTMyLjA3LTE3LjQtMTAuMjctOC42Mi0xNy4yLTIwLjA5LTIyLjYxLTMxLjkyYTE3Mi4zLDE3Mi4zLDAsMCwxLTIuNjQtMTM2LjYyYzEzLjM0LTMyLjMyLDM3LTYzLjQzLDMzLjE0LTk3Ljg0LTUuNzktNTEuMjYtNTctOTYuNjEtMzUuNDctMTUwLjg2QzY0LjMyLDQ1LjU2LDEyNi4xLDYuMDgsMTkyLjY3LDIzLjA3WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0iIzY4ZTFmZCIgb3BhY2l0eT0iMC4xOCIgc3R5bGU9Imlzb2xhdGlvbjogaXNvbGF0ZSIvPg0KICA8cGF0aCBkPSJNMTY1LjU3LDU2OS40OWMtNC41NiwxLjI5LTkuNzQsMy4xNC0xMS4zMyw3LjYtMS40NSw0LjA5LDEsOC43Niw0LjY1LDExLjE0czguMTEsMywxMi40NCwzLjM0YzEzLDEuMDYsMjYsLjQ4LDM5LS4wOWw4MC40MS0zLjU3YzE1LjczLS42OSwzMi40MS0xLjcsNDUuMzItMTAuNzIsMi0xLjM5LDQtMy40NSwzLjU3LTUuODItLjM1LTEuNzgtMi0zLTMuNTktMy44NC0xNC03LjgtMzEuMTMtNi4zMy00Ny4xNi03LjUtMjEuMTUtMS41NS00Mi4wNi04LjIxLTYzLjM4LTcuMzNDMjA1LjI1LDU1My40OSwxODUuMSw1NjMuOTQsMTY1LjU3LDU2OS40OVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIG9wYWNpdHk9IjAuNTIiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50KSIgc3R5bGU9Imlzb2xhdGlvbjogaXNvbGF0ZSIvPg0KICA8cGF0aCBkPSJNMCwxMTUuOTNsNC4xLTEuODFoMTg4djEzNC4xczAsMjEuNDUtMTUuNTYsMzAuMTRDMTcwLjE4LDI4MS45MywwLDExNS45MywwLDExNS45M1oiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9IiM2OGUxZmQiLz4NCiAgPHBhdGggZD0iTTE4OS4yNywxMTUuOTNWMjU1LjIyYTI3LjQ1LDI3LjQ1LDAsMCwxLTI3LjQ1LDI3LjQ0SDBWMTE1LjkzWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0iIzY4ZTFmZCIvPg0KICA8cGF0aCBkPSJNMTg5LjI3LDExNS45M1YyNTUuMjJhMjcuNDUsMjcuNDUsMCwwLDEtMjcuNDUsMjcuNDRIMFYxMTUuOTNaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0yKSIvPg0KICA8cGF0aCBkPSJNMTg5LjI3LDI1NS4yMmEyNy40NSwyNy40NSwwLDAsMS0yNy40NSwyNy40NGgtNC4zM2M5LjU5LTMuMDksOC4zNS0yMC4xLDguMzUtMjAuMUMxODMuNzgsMjY1LjY1LDE4OS4yNywyNTUuMjIsMTg5LjI3LDI1NS4yMloiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9IiM2OGUxZmQiLz4NCiAgPHJlY3QgeD0iMjUwLjQ1IiB5PSIxNTYuMTMiIHdpZHRoPSIxODkuMjYiIGhlaWdodD0iMTY2LjczIiBmaWxsPSIjNjhlMWZkIi8+DQogIDxyZWN0IHg9IjI1MC40NSIgeT0iMTU2LjEzIiB3aWR0aD0iMTg5LjI2IiBoZWlnaHQ9IjE2Ni43MyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMykiLz4NCiAgPHJlY3QgeD0iNDY0Ljg1IiB5PSI4OC43MiIgd2lkdGg9IjE4OS4yNiIgaGVpZ2h0PSIxNjYuNzMiIGZpbGw9IiM2OGUxZmQiLz4NCiAgPHJlY3QgeD0iNDY0Ljg1IiB5PSI4OC43MiIgd2lkdGg9IjE4OS4yNiIgaGVpZ2h0PSIxNjYuNzMiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTQpIi8+DQogIDxwYXRoIGQ9Ik0xMjAuNDcsOTEuMjQsOTMuNjYsMTUyLjcyYzAtLjYzLDAtMS4yNi0uMDYtMS44OC0xLjUuNTYtMi41Mi0xLjEzLTMtMi42Ny0uODItMi40NC0xLjg1LTUuNDItNC4yMS01LjI1LTEuMjMuMDktMi40MiwxLjA4LTMuNTEsMmE4LjQ0LDguNDQsMCwwLDEtMy40NywyLjI5LDEuOTIsMS45MiwwLDAsMS0yLjMtMS40NWgwYTEuODQsMS44NCwwLDAsMSwwLS43NGwtMi41MSwxLjY1Yy0yLjQxLDEuNTctMS4yNi0yLjA3LTEuODEtMy4yOGExMSwxMSwwLDAsMC0zLjk0LDIuNDhMOTcuMSw4MVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9IiM2OGUxZmQiIG9wYWNpdHk9IjAuMzQiIHN0eWxlPSJpc29sYXRpb246IGlzb2xhdGUiLz4NCiAgPHBhdGggZD0iTTMxMy41NSwxNjkuMjdjLjU3LS4yNSwxLjEzLS41MywxLjY5LS44My0xLjEzLTEuMTQsMC0yLjc1LDEuMTktMy44NiwxLjg5LTEuNzQsNC4xOC0zLjksMy4wNi02LS41OS0xLjA5LTItMS43OC0zLjMxLTIuMzdhOC4zNSw4LjM1LDAsMCwxLTMuNS0yLjIyLDEuOTEsMS45MSwwLDAsMSwxLTNjLS44NS0uNTMtMS42OS0xLjA3LTIuNTMtMS42MS0yLjQzLTEuNTUsMS4zNy0yLDIuMjQtM2ExMC45LDEwLjksMCwwLDAtMy44Ny0yLjU5bDY1LjU2LS43NWE1LjMxLDUuMzEsMCwwLDAtMSwyLjc5YzAsMS4wOSwxLjY5LDEuODUsMi4xOSwyLjY4LjA2LjExLjExLjIyLjE2LjMzbC4yNywxLjI3YTQuNjMsNC42MywwLDAsMS0uODQsMi40LDEyLjE4LDEyLjE4LDAsMCwwLTEuODQsMy4yOCw2LjI3LDYuMjcsMCwwLDAsLjgxLDQuMTljMSwyLDIuNTQsMy44Niw0LjY4LDQuNDVoLjJsLjg0LDRaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjNjhlMWZkIiBvcGFjaXR5PSIwLjM0IiBzdHlsZT0iaXNvbGF0aW9uOiBpc29sYXRlIi8+DQogIDxwYXRoIGQ9Ik01MjUuNTEsODUuMjFjLjYzLDAsMS4yNi4wNywxLjg5LjA3LS40NS0xLjUzLDEuMy0yLjQyLDIuODgtMi44MiwyLjQ5LS42Myw1LjU0LTEuNDQsNS41NS0zLjgsMC0xLjI0LS45LTIuNS0xLjc5LTMuNjZhOC40NSw4LjQ1LDAsMCwxLTItMy42MiwxLjkxLDEuOTEsMCwwLDEsMS41OC0yLjE5LDEuOTQsMS45NCwwLDAsMSwuNzYsMGwtMS40Ni0yLjYzYy0xLjM5LTIuNTIsMi4xNi0xLjEsMy40MS0xLjU2YTExLDExLDAsMCwwLTIuMTctNC4xMkw1OTIuMSw5MS40OWE1LjQxLDUuNDEsMCwwLDAtMi4xOSwyYy0uNTIsMSwuNjIsMi40My42NSwzLjRhMS4xNSwxLjE1LDAsMCwxLDAsLjM3bC0uMzQsMS4yM2E1LDUsMCwwLDEtMS44OSwxLjcyLDExLjQ2LDExLjQ2LDAsMCwwLTMuMTgsMiw2LjI3LDYuMjcsMCwwLDAtMS4yOSw0LjA3Yy0uMDcsMi4yMi4zOSw0LjYxLDIsNi4xNWEuNjUuNjUsMCwwLDAsLjE2LjEzbC0xLjE5LDMuOTNaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjNjhlMWZkIiBvcGFjaXR5PSIwLjM0IiBzdHlsZT0iaXNvbGF0aW9uOiBpc29sYXRlIi8+DQogIDxwYXRoIGQ9Ik0xMjAuNDcsOTEuMjQsOTMuNjYsMTUyLjcyYzAtLjYzLDAtMS4yNi0uMDYtMS44OC0xLjUuNTYtMi41Mi0xLjEzLTMtMi42Ny0uODItMi40NC0xLjg1LTUuNDItNC4yMS01LjI1LTEuMjMuMDktMi40MiwxLjA4LTMuNTEsMmE4LjQ0LDguNDQsMCwwLDEtMy40NywyLjI5LDEuOTIsMS45MiwwLDAsMS0yLjMtMS40NWgwYTEuODQsMS44NCwwLDAsMSwwLS43NGwtMi41MSwxLjY1Yy0yLjQxLDEuNTctMS4yNi0yLjA3LTEuODEtMy4yOGExMSwxMSwwLDAsMC0zLjk0LDIuNDhMOTcuMSw4MVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9IiNmZmYiIG9wYWNpdHk9IjAuMzQiIHN0eWxlPSJpc29sYXRpb246IGlzb2xhdGUiLz4NCiAgPHBhdGggZD0iTTMxMy41NSwxNjkuMjdjLjU3LS4yNSwxLjEzLS41MywxLjY5LS44My0xLjEzLTEuMTQsMC0yLjc1LDEuMTktMy44NiwxLjg5LTEuNzQsNC4xOC0zLjksMy4wNi02LS41OS0xLjA5LTItMS43OC0zLjMxLTIuMzdhOC4zNSw4LjM1LDAsMCwxLTMuNS0yLjIyLDEuOTEsMS45MSwwLDAsMSwxLTNjLS44NS0uNTMtMS42OS0xLjA3LTIuNTMtMS42MS0yLjQzLTEuNTUsMS4zNy0yLDIuMjQtM2ExMC45LDEwLjksMCwwLDAtMy44Ny0yLjU5bDY1LjU2LS43NWE1LjMxLDUuMzEsMCwwLDAtMSwyLjc5YzAsMS4wOSwxLjY5LDEuODUsMi4xOSwyLjY4LjA2LjExLjExLjIyLjE2LjMzbC4yNywxLjI3YTQuNjMsNC42MywwLDAsMS0uODQsMi40LDEyLjE4LDEyLjE4LDAsMCwwLTEuODQsMy4yOCw2LjI3LDYuMjcsMCwwLDAsLjgxLDQuMTljMSwyLDIuNTQsMy44Niw0LjY4LDQuNDVoLjJsLjg0LDRaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjZmZmIiBvcGFjaXR5PSIwLjM0IiBzdHlsZT0iaXNvbGF0aW9uOiBpc29sYXRlIi8+DQogIDxwYXRoIGQ9Ik01MjUuNTEsODUuMjFjLjYzLDAsMS4yNi4wNywxLjg5LjA3LS40NS0xLjUzLDEuMy0yLjQyLDIuODgtMi44MiwyLjQ5LS42Myw1LjU0LTEuNDQsNS41NS0zLjgsMC0xLjI0LS45LTIuNS0xLjc5LTMuNjZhOC40NSw4LjQ1LDAsMCwxLTItMy42MiwxLjkxLDEuOTEsMCwwLDEsMS41OC0yLjE5LDEuOTQsMS45NCwwLDAsMSwuNzYsMGwtMS40Ni0yLjYzYy0xLjM5LTIuNTIsMi4xNi0xLjEsMy40MS0xLjU2YTExLDExLDAsMCwwLTIuMTctNC4xMkw1OTIuMSw5MS40OWE1LjQxLDUuNDEsMCwwLDAtMi4xOSwyYy0uNTIsMSwuNjIsMi40My42NSwzLjRhMS4xNSwxLjE1LDAsMCwxLDAsLjM3bC0uMzQsMS4yM2E1LDUsMCwwLDEtMS44OSwxLjcyLDExLjQ2LDExLjQ2LDAsMCwwLTMuMTgsMiw2LjI3LDYuMjcsMCwwLDAtMS4yOSw0LjA3Yy0uMDcsMi4yMi4zOSw0LjYxLDIsNi4xNWEuNjUuNjUsMCwwLDAsLjE2LjEzbC0xLjE5LDMuOTNaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjZmZmIiBvcGFjaXR5PSIwLjM0IiBzdHlsZT0iaXNvbGF0aW9uOiBpc29sYXRlIi8+DQogIDxyZWN0IHg9IjQ5NSIgeT0iMTU0LjQzIiB3aWR0aD0iMTI4Ljk2IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTUpIi8+DQogIDxyZWN0IHg9IjQ5NSIgeT0iMTgwLjAyIiB3aWR0aD0iMTI4Ljk2IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTYpIi8+DQogIDxyZWN0IHg9IjQ5NSIgeT0iMjA1LjYyIiB3aWR0aD0iMTI4Ljk2IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTcpIi8+DQogIDxyZWN0IHg9IjQ3LjI4IiB5PSIxNzEuOTkiIHdpZHRoPSI5NC43IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTgpIi8+DQogIDxyZWN0IHg9IjQ3LjI4IiB5PSIxOTcuNTkiIHdpZHRoPSI5NC43IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTkpIi8+DQogIDxyZWN0IHg9IjQ3LjI4IiB5PSIyMjMuMTkiIHdpZHRoPSI5NC43IiBoZWlnaHQ9IjMuNDEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTEwKSIvPg0KICA8cmVjdCB4PSIyOTYuMjEiIHk9IjE5OS4zIiB3aWR0aD0iOTQuNyIgaGVpZ2h0PSIzLjQxIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xMSkiLz4NCiAgPHJlY3QgeD0iMjk2LjIxIiB5PSIyMjQuOSIgd2lkdGg9Ijk0LjciIGhlaWdodD0iMy40MSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTIpIi8+DQogIDxyZWN0IHg9IjI5Ni4yMSIgeT0iMjUwLjQ5IiB3aWR0aD0iOTQuNyIgaGVpZ2h0PSIzLjQxIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xMykiLz4NCiAgPHBhdGggZD0iTTE4OS4yNywyOTZzMzQuMDYtNTkuMzUsNDYtNzguMTNsNy42Ni05LjI4LDcuNTEsMTIuNzcuMTcsMTAuMjgtMzEuNDIsNTkuMjFTMTk2LjczLDMxMS4zOSwxODkuMjcsMjk2WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0iIzY4ZTFmZCIvPg0KICA8cG9seWdvbiBwb2ludHM9IjI1MC45NSAyMTAuMTYgMjEzLjUgMjg2LjI1IDI0MC4yOSAyNTIuMiAyNTAuNjQgMjMxLjY4IDI1MC45NSAyMTAuMTYiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTE0KSIvPg0KICA8cGF0aCBkPSJNMjk0LjkzLDIwNS42MWExMC4yMywxMC4yMywwLDAsMSwxLjkzLDYuNzljNC41Ni0zLjc0LDQuNjMtMTEuNiw5LjgyLTE0LjQxYTI1LjYsMjUuNiwwLDAsMS0xLjU3LDguODNjMS42NS0zLjQsMy42OC03LjE1LDcuMzEtOC4yM2EyNCwyNCwwLDAsMS00LjEzLDEwLjc3bDQuNzMtNC43OGMuNDItLjQzLDEtLjksMS41Ny0uNjFzLjQyLDEuMjguMTEsMS45NGwtNS4yMiwxMS4xNmEyOC40OCwyOC40OCwwLDAsMSw1LjM1LTMuNGwtNS43Myw5LjQ0YTE2LjE3LDE2LjE3LDAsMCwxLTIuMzgsMy4zMWMtMi4xMywyLjE0LTUuNTIsMy4zOS02LjI1LDYuMzIuMTYtLjYzLTguMjQtMy4zMS04LjgzLTQuMjItMS0xLjU3Ljg0LTQuODcsMS4wNS02Ljc1QzI5My4yOSwyMTYuNDksMjkxLjg1LDIxMC4zOSwyOTQuOTMsMjA1LjYxWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTUpIi8+DQogIDxwYXRoIGQ9Ik0yNDQuODcsMzk3LjM1bDExLjU0LDg0LjA2YTIyLjQ4LDIyLjQ4LDAsMCwxLTEuMDgsMTAuNTFMMjQyLjUyLDU1MS4xLDIyMi42Niw1NDlsOS4wOS02MC40N2E4LjU1LDguNTUsMCwwLDAtLjIzLTMuNzNsLTE1LjY2LTU0LTMsNjEuMTYtMjUuNjcsNTItMTgtNy4yTDE5Mi4wNSw0OTBsLTMuNjctNTcuNzZjLTMuMjUtMjAuMSwyLjY5LTM0Ljk0LDIuNjktMzQuOTRaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjM2YzZDU2Ii8+DQogIDxyZWN0IHg9IjE5MS4wMyIgeT0iMzg4LjQiIHdpZHRoPSI1My44NCIgaGVpZ2h0PSI4Ljk1IiBmaWxsPSIjNjhlMWZkIi8+DQogIDxyZWN0IHg9IjE5MS4wMyIgeT0iMzg4LjQiIHdpZHRoPSI1My44NCIgaGVpZ2h0PSI4Ljk1IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xNikiLz4NCiAgPHBhdGggZD0iTTMwNCwyMzQuNmwtNTAuNjUsODMuNjYtMi42NCw2Mi43OWMwLDYtLjI0LDExLTQuNywxMi4zN2E5LjI5LDkuMjksMCwwLDEtMi42Ny4zNUgxOTguNTNBMTIuODIsMTIuODIsMCwwLDEsMTg1LjcxLDM4MWgwVjMyMy4yOHMtMy4zLTMyLjcxLDEyLjIyLTMyLjcxSDIyOWEyNC41LDI0LjUsMCwwLDAsMTkuMjctOS4zM2w0MS40Ni01NC42M1oiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9IiM2OGUxZmQiLz4NCiAgPHJlY3QgeD0iMjEwLjk4IiB5PSIyNTEuMzciIHdpZHRoPSIxNS41NCIgaGVpZ2h0PSIzOS41MSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTcpIi8+DQogIDxwYXRoIGQ9Ik0yMTEsMjQ3LjA1djQzLjg0aDguMnYtMi42N2E1LjkyLDUuOTIsMCwwLDEsNS45Mi01LjkyaC40N2ExNC43MiwxNC43MiwwLDAsMCwxNC43Mi0xNC43MmgwVjI0Ny4wNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTE4KSIvPg0KICA8cGF0aCBkPSJNMjQ2LjM4LDIwOC43MWMuMzEtLjY1LjU0LTEuMzMuODgtMmExNC4wOSwxNC4wOSwwLDAsMSwyLjYtMy4yMWwzLjI0LTMuM2ExLjU3LDEuNTcsMCwwLDEsLjg4LS41NmMuNjctLjA4LDEuMTQuNzQsMSwxLjRhNC4yMyw0LjIzLDAsMCwxLTEsMS42OCwxNSwxNSwwLDAsMC0zLDcuNDEsNjMuOTQsNjMuOTQsMCwwLDAtLjM3LDguMDcsNC45NCw0Ljk0LDAsMCwxLS41MiwyLjU2LDczLjMyLDczLjMyLDAsMCwwLTMuMzgtNi41M2MtLjQzLS43Mi0xLjc0LTIuMTMtMS43OC0yLjk0UzI0Ni4xLDIwOS40MiwyNDYuMzgsMjA4LjcxWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTkpIi8+DQogIDxwYXRoIGQ9Ik0yNDEuNzEsMjQwLjE1YTExLDExLDAsMCwwLTUuMDctNy40VjIzNWMtNS44MS0yLjgxLTEyLjc2LS42LTE5LjEzLTEuNjVhOSw5LDAsMCwxLDEuNzYsMi42NCwyNi44NywyNi44NywwLDAsMC0xMiwyLjgzbDEsMS40NmExLjExLDEuMTEsMCwwLDEsLjIzLjUyYzAsLjM5LS4zNy42NS0uNjguODktMS44LDEuMzctMiw0LTEuOSw2LjI2LjMzLDYuODQsMi4xLDEzLjUxLDMuODYsMjAuMTMuNjcsMi41MSwxLjMzLDUsMiw3LjUzbDEuNC0xLjkzLDEuMzMuOTNjMS44Mi0yLjgyLDkuNzYtMy40MSwxMC40OC02LjY5LTItLjQ2LTQuMzktMy4xNy00LjE3LTUuMjJzLjg4LTIuNTEsMi44My0xLjg1YzEuMzYuNDUtLjg3LTIuMzMtMS4xMS0zLjQ2cy0uNzUtMi4yOC0uMTktMy4yNWMuNzctMS4zNSwyLjc4LTEsNC4yMi0uNDRhOC43Nyw4Ljc3LDAsMCwxLDguNzQtNS44NmMyLC4xNSwzLjkzLDEuMzYsNS4yNS0uNTRTMjQyLjEsMjQyLjM1LDI0MS43MSwyNDAuMTVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgwIDApIiBmaWxsPSIjM2YzZDU2Ii8+DQogIDxwYXRoIGQ9Ik0zMDQsMjM0LjZsLTUwLjY1LDgzLjY2LTIuNjQsNjIuNzljMCw2LC4xMSwxMS44Mi02LjE4LDEyLjcySDIzNi4xczcuMTItNzEuOCw1LjgxLTc4Ljc2LDU4LjYtODIuMjgsNTguNi04Mi4yOFoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDAgMCkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTIwKSIvPg0KICA8cGF0aCBkPSJNMjI2LDU0OS4zMmwtMy40NywxNWg0NXMuNDctNy40Mi04LjgxLTEwYTM2LjIyLDM2LjIyLDAsMCwwLTE3LjE2LS40N2wtMS4xOS0zWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0iIzNmM2Q1NiIvPg0KICA8cGF0aCBkPSJNMTcyLjg3LDUzOC4yMWwtNy45MiwxMiw5LjI4LDUuNDEsMi45My0xLjU0LDYuNjUsNi44LDIzLjM1Ljc3cy0xLjU0LTExLjY4LTEyLjM3LTExLjcxLTkuODctNi45LTkuODctNi45WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMCAwKSIgZmlsbD0iIzNmM2Q1NiIvPg0KPC9zdmc+DQo=');
        background-repeat: no-repeat;
        display: flex;
        padding: 150px 100px;
        overflow: hidden;
        padding-bottom: 15px;
        opacity: 1;
    }
    .theme h2.slogan {
      position: absolute;
      left: 50%;
      transform: translateX(-50%);
      top: 50px;
      font-size: 35px;
      text-transform: uppercase;
      font-weight: 100;
      color:rgba(34, 181, 111, 1);
      border-bottom: 1px dashed currentColor;
    }
    .theme-table {
      display: flex;
      flex-direction: column;
      /* flex-grow: 1; */
      width: 45%;
      height: auto;
      background:#fff;
      box-shadow: 0px 0px 12px 2px #b0b0b0;
      /* margin-right: 30px; */
      padding: 20px;
      color: #666;
    }
    .theme-table h3 {
      margin-bottom: 25px;
      margin-top: 25px;
      font-weight: normal;
      font-size: 25px;
    }
    .theme-table table {
      margin-bottom: 20px;
    }
    .theme-table code {
      background: #E9F9F9;
      padding: 5px 10px;
      margin-bottom: 20px;
      border-radius: 5px;
      font-size: 14px;
      color: #666 !important;
    }
    .theme-table blockquote {
      border-left: 3px solid rgb(34, 181, 111);
      padding-left: 10px;
      margin-left: 20px;
    }
    .themes-option {
      width: 55%;
      padding: 180px 50px 0 50px;
      color: #666;
    }
    .themes-option label {
      margin-right: 25px;
      margin-left: 15px;
      cursor: pointer;
      color: #666;
    }
    .themes-option .light {
      margin-bottom: 20px;
    }
    input {
      cursor: pointer;
    }
    .light .option-one, input#one-l {
      color: rgba(34, 181, 111, 1);
    }
    .light .option-two, input#two-l {
    color: #6886aa;
    }
    .light .option-three, input#three-l {
      color: rgb(12, 139, 186);
    }
    .dark .option-one, input#one-d {
      color: #333;
    }
    .dark .option-two, input#two-d {
      color: rgb(244, 130, 55);
    }
    .dark .option-three, input#three-d {
      color: rgb(226, 192, 141);
    }
    input::before {
      content: '';
      position: absolute;
      top: 0;
      width: 18px;
      height: 18px;
      border-radius: 50%;
      background: currentColor;
      box-shadow: 0px 0px 13px 0px currentColor;
    }
    input[type="radio"]::after {
      content: '';
      transform: rotate(-45deg) scale(0);
      width: 8px;
      height: 4px;
      border: 2px solid #fff;
      border-top: none;
      border-right: none;
      position: absolute;
      display: inline-block;
      top: 5px;
      left: 4px;
    }
    input[type="radio"]:checked:after {
      transform: rotate(-45deg) scale(1);
    }
    input[type="radio"]:checked + label {
      color: currentColor;
    }
    .themes-option h2 {
      font-size: 30px;
      color: #666;
      text-align: center;
      margin-bottom: 20px;
      color: #0c8bba;

    }
    .option {
      display: flex;
      flex-direction: row;
      justify-content: space-around;
      flex: 1;
      flex-wrap: wrap;
    }
    .themes-option .inline{
      display: inline-block;
      font-size: 16px;
      position: relative;
      flex-grow: 1;
      flex-shrink: 0;
      flex-basis: 0%;
    }
    @media screen and (max-width: 950px) {
      .theme {
        height: auto;
        padding: 20px;
        overflow: auto;
        flex-direction: column-reverse;
      }
      .themes-option {
        width: 100%;
        padding: 130px 0px 0px 0px;
        margin-bottom: 30px;
      }
      .theme-table {
        width: 100%;
      }
      .themes-option h2 {
        font-size: 20px !important;
      }
    }
    .cadmium {
      background: #fff;
      color: #666;
    }
    .graphite {
      background: #6886aa !important;
      color: #fff;
    }
    .ulysses {
      background: rgb(12, 139, 186) !important;
      color: #fff;
    }
    .dark-theme {
      background: #333;
      color: #fff;
    }
    .material {
      background: rgb(244, 130, 55);
      color: #fff;
    }
    .one-dark {
      background: rgb(226, 192, 141);
      color: #fff;
    }
</style>

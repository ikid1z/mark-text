<template>
  <div class="sponsor" id="sponsor">
    <h2 class="slogan">Sponsor😀</h2>
    <div class="sponsor-list">
        <div class="sponsor-item">
            <h3>Friendship sponsor</h3>
            <div class="list">
                <a href="javascript:void(0);">
                    <img src="../assets/new_logo.min.png" alt="">
                </a>
            </div>
        </div>
        <div class="sponsor-item">
            <h3>Platinum sponsor</h3>
            <div class="list">
                <a href="javascript:void(0);">
                    <img src="../assets/readme-blue.png" alt="">
                </a>
            </div>
            <div class="list">
                <a href="javascript:void(0);">
                    <img src="../assets/qordoba.svg" alt="">
                </a>
            </div>
        </div>
    </div>
    <div class="sponsor-detail">
        <h3>Sponsor Mark Text Development</h3>
        <p>Mark Text is an MIT licensed open source project,you will always be able to download the latest version from <a href="#">GitHub release page</a>. Mark Text is still in development, and its development is inseparable from all sponsors. I hope you join them:</p>
        <div class="d-flex">
            <a href="javascript:void(0);" class="detail-link">
                <img src="https://opencollective.com/static/images/opencollective-icon.svg" alt="" width="25px" height="25px">
                <img src="https://opencollective.com/static/images/logotype.svg" alt="" width="120px" height="auto">
            </a>
            <a href="javascript:void(0);" class="detail-link">
                Become A Patreon
            </a>
        </div>
        <div class="sponsor-des">
            <strong>What's the difference between Patreon and OpenCollective?</strong>
            <p>Sponsored by Patreon, goes directly to support Ran Luo's work on Mark Text. Sponsored by Open Collective, all expenses are transparent, and used for the development of Mark Text.</p>
            <strong>We also accept One Time Donations</strong>
        </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Sponsor'
}
</script>

<style>
    a {
        display: block;
    }
    .list a img {
    width: 100%;
    height: 100%;
    }
    .sponsor {
        background-color:#FEF7F7 !important;
        position: relative;
        height: 100vh;
        width: 100%;
        position: relative;
        background-size: 250px 250px;
        background-position: 35% 90%;
        background-image: url('data:image/svg+xml;base64,DQo8c3ZnIGlkPSJMYXllcl8xIiBkYXRhLW5hbWU9IkxheWVyIDEiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgeG1sbnM6eGxpbms9Imh0dHA6Ly93d3cudzMub3JnLzE5OTkveGxpbmsiIHZpZXdCb3g9IjAgMCA1MTYuNjIgNDQwLjkzIj48ZGVmcz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudCIgeDE9IjIwOC4zNSIgeTE9IjQxNC4xNyIgeDI9IjI4NC4yNSIgeTI9IjQ1OC4wOSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPjxzdG9wIG9mZnNldD0iMCIgc3RvcC1vcGFjaXR5PSIwIi8+PHN0b3Agb2Zmc2V0PSIwLjk5Ii8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yIiB4MT0iMzM4LjExIiB5MT0iNDE3LjIxIiB4Mj0iMzE0LjUxIiB5Mj0iNDQ2LjE5IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMyIgeDE9IjQuNjciIHkxPSIyNTUuNjIiIHgyPSI5MzQuNTkiIHkyPSI0MTguMTgiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC00IiB4MT0iMzYzLjciIHkxPSIyNTUuNjIiIHgyPSIxMjkzLjYyIiB5Mj0iNDE4LjE4IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNSIgeDE9IjE2Mi44IiB5MT0iMzQyLjcxIiB4Mj0iNjI4LjM1IiB5Mj0iMzI3LjE4IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNiIgeDE9IjE5Ni45NCIgeTE9IjEyMC42NCIgeDI9IjE2Ny4wNSIgeTI9IjcwMy45MyIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTciIHgxPSIxOTQuNDMiIHkxPSIyMzQuMTUiIHgyPSIxOTguOTEiIHkyPSIxNy4yMSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPjxzdG9wIG9mZnNldD0iMCIgc3RvcC1jb2xvcj0iI2ZmZiIgc3RvcC1vcGFjaXR5PSIwIi8+PHN0b3Agb2Zmc2V0PSIwLjk5IiBzdG9wLWNvbG9yPSIjZmZmIi8+PC9saW5lYXJHcmFkaWVudD48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC04IiB4MT0iMjM0LjczIiB5MT0iMTM0LjE1IiB4Mj0iNzI0LjE5IiB5Mj0iMTY0LjAzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtOSIgeDE9IjI4NS4zOCIgeTE9IjEwOC40NSIgeDI9IjMyMS4yMyIgeTI9IjEwOC40NSIgZ3JhZGllbnRVbml0cz0idXNlclNwYWNlT25Vc2UiPjxzdG9wIG9mZnNldD0iMCIgc3RvcC1jb2xvcj0iI2VjYzRkNyIvPjxzdG9wIG9mZnNldD0iMC40MiIgc3RvcC1jb2xvcj0iI2VmZDRkMSIvPjxzdG9wIG9mZnNldD0iMSIgc3RvcC1jb2xvcj0iI2YyZWFjOSIvPjwvbGluZWFyR3JhZGllbnQ+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTAiIHgxPSIyNjcuNDYiIHkxPSIyMDYuMjciIHgyPSI3NTQuMjMiIHkyPSIyNjEuODUiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xMSIgeDE9IjI1MC40MiIgeTE9IjIyOC41OCIgeDI9IjY5MS40NyIgeTI9IjQ4MS4zOCIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTEyIiB4MT0iMjgxLjc5IiB5MT0iMzk5LjA0IiB4Mj0iMzI4LjQxIiB5Mj0iODIuODkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xMyIgeDE9IjI4NC42OCIgeTE9IjM0Mi43MSIgeDI9IjQzMS4xIiB5Mj0iNzAuNzkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTE0IiB4MT0iMzE0LjI1IiB5MT0iNDE5LjU4IiB4Mj0iMzIwLjIzIiB5Mj0iMjYzLjMiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xNSIgeDE9IjMwNy42NSIgeTE9IjQyOC42OCIgeDI9IjM2NC43MiIgeTI9IjQ3My41IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMTYiIHgxPSIyMDEuODQiIHkxPSIyMTMuMzMiIHgyPSIyMDEuNjQiIHkyPSIxNTUuNTUiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0xNyIgeDE9IjIwMC44NiIgeTE9IjIwNC41NCIgeDI9IjIwMi41NCIgeTI9IjI1MC41NiIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTE4IiB4MT0iMjk2LjEiIHkxPSI4My4yNiIgeDI9IjMzNS41NCIgeTI9IjEwNy43NiIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudCIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTE5IiB4MT0iMjUzLjA5IiB5MT0iMTkxLjg4IiB4Mj0iMjIzLjgiIHkyPSIxNTkuMDEiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTIwIiB4MT0iMTU5LjQ5IiB5MT0iMjIyLjA4IiB4Mj0iMTkyLjIzIiB5Mj0iMjIyLjA4IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTkiLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yMSIgeDE9Ijg3Ljk0IiB5MT0iMTI5LjY4IiB4Mj0iMTYxLjc1IiB5Mj0iMTE3LjEzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yMiIgeDE9IjE0OC43NiIgeTE9IjM1LjcyIiB4Mj0iMTQ3LjI3IiB5Mj0iMTE1LjUxIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yMyIgeDE9IjE0My41NSIgeTE9IjM1LjYzIiB4Mj0iMTQyLjA2IiB5Mj0iMTE1LjQxIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yNCIgeDE9IjE4NC41NSIgeTE9IjM2LjM5IiB4Mj0iMTgzLjA1IiB5Mj0iMTE2LjE4IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yNSIgeDE9IjIzMC4xMiIgeTE9IjM3LjI1IiB4Mj0iMjI4LjYzIiB5Mj0iMTE3LjAzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yNiIgeDE9IjE1NS4zNCIgeTE9IjM1Ljg1IiB4Mj0iMTUzLjg0IiB5Mj0iMTE1LjYzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yNyIgeDE9IjE2NC45IiB5MT0iMzYuMDIiIHgyPSIxNjMuNCIgeTI9IjExNS44MSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtMjgiIHgxPSIxOTEuNTkiIHkxPSIzNi41MiIgeDI9IjE5MC4xIiB5Mj0iMTE2LjMxIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0yOSIgeDE9IjE2MS44NCIgeTE9IjM1Ljk3IiB4Mj0iMTYwLjM1IiB5Mj0iMTE1Ljc1IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zMCIgeDE9IjI0My4yNyIgeTE9IjM3LjQ5IiB4Mj0iMjQxLjc4IiB5Mj0iMTE3LjI4IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zMSIgeDE9IjE5NS45MyIgeTE9IjM2LjYxIiB4Mj0iMTk0LjQ0IiB5Mj0iMTE2LjM5IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zMiIgeDE9IjIyNi40MSIgeTE9IjM3LjE4IiB4Mj0iMjI0LjkxIiB5Mj0iMTE2Ljk2IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zMyIgeDE9IjE0OC43NiIgeTE9IjU2LjM0IiB4Mj0iMTQ3LjI3IiB5Mj0iMTM2LjEzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zNCIgeDE9IjE0My41NSIgeTE9IjU2LjI0IiB4Mj0iMTQyLjA2IiB5Mj0iMTM2LjAzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zNSIgeDE9IjE4NC41NSIgeTE9IjU3LjAxIiB4Mj0iMTgzLjA1IiB5Mj0iMTM2LjgiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTM2IiB4MT0iMjMwLjEyIiB5MT0iNTcuODYiIHgyPSIyMjguNjMiIHkyPSIxMzcuNjUiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTM3IiB4MT0iMTU1LjM0IiB5MT0iNTYuNDYiIHgyPSIxNTMuODQiIHkyPSIxMzYuMjUiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTM4IiB4MT0iMTY0LjkiIHkxPSI1Ni42NCIgeDI9IjE2My40IiB5Mj0iMTM2LjQzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC0zOSIgeDE9IjE5MS41OSIgeTE9IjU3LjE0IiB4Mj0iMTkwLjEiIHkyPSIxMzYuOTMiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTQwIiB4MT0iMTYxLjg0IiB5MT0iNTYuNTkiIHgyPSIxNjAuMzUiIHkyPSIxMzYuMzciIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTQxIiB4MT0iMjQzLjI3IiB5MT0iNTguMTEiIHgyPSIyNDEuNzgiIHkyPSIxMzcuODkiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTQyIiB4MT0iMTk1LjkzIiB5MT0iNTcuMjIiIHgyPSIxOTQuNDQiIHkyPSIxMzcuMDEiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTQzIiB4MT0iMjI2LjQxIiB5MT0iNTcuOCIgeDI9IjIyNC45MSIgeTI9IjEzNy41OCIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDQiIHgxPSIxNDguNzYiIHkxPSI3Ni45NiIgeDI9IjE0Ny4yNyIgeTI9IjE1Ni43NCIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDUiIHgxPSIxNDMuNTUiIHkxPSI3Ni44NiIgeDI9IjE0Mi4wNiIgeTI9IjE1Ni42NSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDYiIHgxPSIxODQuNTUiIHkxPSI3Ny42MyIgeDI9IjE4My4wNSIgeTI9IjE1Ny40MSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDciIHgxPSIyMzAuMTIiIHkxPSI3OC40OCIgeDI9IjIyOC42MyIgeTI9IjE1OC4yNyIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDgiIHgxPSIxNTUuMzQiIHkxPSI3Ny4wOCIgeDI9IjE1My44NCIgeTI9IjE1Ni44NyIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNDkiIHgxPSIxNjQuOSIgeTE9Ijc3LjI2IiB4Mj0iMTYzLjQiIHkyPSIxNTcuMDUiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjxsaW5lYXJHcmFkaWVudCBpZD0ibGluZWFyLWdyYWRpZW50LTUwIiB4MT0iMTkxLjU5IiB5MT0iNzcuNzYiIHgyPSIxOTAuMSIgeTI9IjE1Ny41NSIgeGxpbms6aHJlZj0iI2xpbmVhci1ncmFkaWVudC03Ii8+PGxpbmVhckdyYWRpZW50IGlkPSJsaW5lYXItZ3JhZGllbnQtNTEiIHgxPSIxNjEuODQiIHkxPSI3Ny4yIiB4Mj0iMTYwLjM1IiB5Mj0iMTU2Ljk5IiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC01MiIgeDE9IjI0My4yNyIgeTE9Ijc4LjczIiB4Mj0iMjQxLjc4IiB5Mj0iMTU4LjUxIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC01MyIgeDE9IjE5NS45MyIgeTE9Ijc3Ljg0IiB4Mj0iMTk0LjQ0IiB5Mj0iMTU3LjYzIiB4bGluazpocmVmPSIjbGluZWFyLWdyYWRpZW50LTciLz48bGluZWFyR3JhZGllbnQgaWQ9ImxpbmVhci1ncmFkaWVudC01NCIgeDE9IjIyNi40MSIgeTE9Ijc4LjQxIiB4Mj0iMjI0LjkxIiB5Mj0iMTU4LjIiIHhsaW5rOmhyZWY9IiNsaW5lYXItZ3JhZGllbnQtNyIvPjwvZGVmcz48dGl0bGU+RG8gQ29kZTwvdGl0bGU+PHBhdGggZD0iTTMyNS4xMSw0NDAuNWMyNC44OS4zLDQ5Ljg2LjU4LDc0LjU3LTIuNCwxMi4zMy0xLjQ4LDI0Ljc2LTMuODQsMzUuODItOS40OSwxMi4xOC02LjIyLDIyLjA3LTE2LjExLDMxLjEtMjYuMzksMTkuNDktMjIuMTgsMzYuMjEtNDcuMzUsNDUtNzUuNTNzOS4xOC01OS42Ni0yLjg4LTg2LjYxYy04LTE4LTIxLjMzLTMzLjY0LTI2LjI1LTUyLjY4LTguMTYtMzEuNTgsOC4yNy02Ni0xLjM1LTk3LjE3LTMuNjgtMTEuOTItMTEtMjIuNDMtMTkuMjgtMzEuNzQtMzMuMi0zNy4yMy04NS01Ny0xMzQuNTMtNTEuNDEtNjEuOTIsNy0xMTUuODcsNTAuMTQtMTc4LDU0LjI3LTIxLDEuMzktNDIuNDItMS43Ny02MywyLjYtMzYuMDcsNy42NC02NS4zOSw0MC4yNC02OS4xOCw3Ni45MS0yLjUyLDI0LjQ5LDUuMjUsNDguNjgsMTAuNzQsNzIuNjgsNS44LDI1LjM5LDksNTIuMjQsMS44LDc3LjI2LTUuNDQsMTguODQtMTYuNTQsMzUuNjItMjIuNDIsNTQuMzJDMS44LDM2Mi4yOCwxLDM4MC41NSwxLjYyLDM5OC41MmMuMTksNS4zMi41NiwxMC44LDIuODcsMTUuNiw3LjgzLDE2LjIxLDM4LjI4LDIwLjk0LDU0LjI0LDIyLjM3LDI4LjIyLDIuNTUsNTcuNjYuODMsODYsMS4zMlEyMzQuOTQsNDM5LjM5LDMyNS4xMSw0NDAuNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0iIzY4ZTFmZCIgb3BhY2l0eT0iMC4xOCIgc3R5bGU9Imlzb2xhdGlvbjppc29sYXRlIi8+PHBhdGggZD0iTTI1Ni4xOSw0MzEuNDRhNCw0LDAsMCwxLC4xLDIuNDUsMy44OSwzLjg5LDAsMCwxLS43OCwxLjE5Yy0zLjA5LDMuNDktNy43LDUuMTYtMTIuMSw2LjY5YTMyLjQ1LDMyLjQ1LDAsMCwxLTQuNzEsMS4zNiwyOC4wNiwyOC4wNiwwLDAsMS01LjE4LjMxLDE1MC42LDE1MC42LDAsMCwxLTE3LTEuMDhBMjAuMTEsMjAuMTEsMCwwLDEsMjMxLjIxLDQzMGMzLjExLS42MSw2LjMxLS40Niw5LjQ2LS43N2ExLjM1LDEuMzUsMCwwLDAsMS4xNC0uNTIsMS40MSwxLjQxLDAsMCwwLDAtMWwtMS4yNi00LjdhMiwyLDAsMCwxLS4wNy0xLjI0Yy4yMS0uNTguODgtLjg0LDEuNDctMSwyLjEzLS42MiwzLjU0LTYuODcsNS44Mi03czUuNDUsNy4zMyw1Ljg1LDkuN0MyNTQuMSw0MjYuMzksMjU1Ljg2LDQzMC4yMSwyNTYuMTksNDMxLjQ0WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSIjNjhlMWZkIi8+PHBhdGggZD0iTTI1Ni4xOSw0MzEuNDRhNCw0LDAsMCwxLC4xLDIuNDUsMy44OSwzLjg5LDAsMCwxLS43OCwxLjE5Yy0zLjA5LDMuNDktNy43LDUuMTYtMTIuMSw2LjY5YTMyLjQ1LDMyLjQ1LDAsMCwxLTQuNzEsMS4zNiwyOC4wNiwyOC4wNiwwLDAsMS01LjE4LjMxLDE1MC42LDE1MC42LDAsMCwxLTE3LTEuMDhBMjAuMTEsMjAuMTEsMCwwLDEsMjMxLjIxLDQzMGMzLjExLS42MSw2LjMxLS40Niw5LjQ2LS43N2ExLjM1LDEuMzUsMCwwLDAsMS4xNC0uNTIsMS40MSwxLjQxLDAsMCwwLDAtMWwtMS4yNi00LjdhMiwyLDAsMCwxLS4wNy0xLjI0Yy4yMS0uNTguODgtLjg0LDEuNDctMSwyLjEzLS42MiwzLjU0LTYuODcsNS44Mi03czUuNDUsNy4zMyw1Ljg1LDkuN0MyNTQuMSw0MjYuMzksMjU1Ljg2LDQzMC4yMSwyNTYuMTksNDMxLjQ0WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudCkiLz48cGF0aCBkPSJNMzE5LjM1LDQzNy4wNWM1LjkyLDUuNjcsMTQuOTEsNi44NCwyMyw1LjkxLDEuMzctLjE2LDIuOTMtLjQ5LDMuNjEtMS42OXMuMTctMi43MS0uNTYtMy44OGMtMS43Mi0yLjcyLTQuNTEtNC41OC03LjMyLTYuMTZBNjcuMTYsNjcuMTYsMCwwLDAsMzI1LDQyNS42NGE4LDgsMCwwLDEtMi42OC0xLjE5Yy0xLjc3LTEuNC0xLjk0LTQtMy4zNC01LjgtLjU5LS43NS03LjI2LTIuNTQtNy45MS0yLTIsMS41NC4zOSw2LjQsMS4yNiw4LjY4QzMxNCw0MjkuNTYsMzE2LDQzMy44NCwzMTkuMzUsNDM3LjA1WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSIjNjhlMWZkIi8+PHBhdGggZD0iTTMxOS4zNSw0MzcuMDVjNS45Miw1LjY3LDE0LjkxLDYuODQsMjMsNS45MSwxLjM3LS4xNiwyLjkzLS40OSwzLjYxLTEuNjlzLjE3LTIuNzEtLjU2LTMuODhjLTEuNzItMi43Mi00LjUxLTQuNTgtNy4zMi02LjE2QTY3LjE2LDY3LjE2LDAsMCwwLDMyNSw0MjUuNjRhOCw4LDAsMCwxLTIuNjgtMS4xOWMtMS43Ny0xLjQtMS45NC00LTMuMzQtNS44LS41OS0uNzUtNy4yNi0yLjU0LTcuOTEtMi0yLDEuNTQuMzksNi40LDEuMjYsOC42OEMzMTQsNDI5LjU2LDMxNiw0MzMuODQsMzE5LjM1LDQzNy4wNVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMikiLz48cmVjdCB4PSI0MTEuNTIiIHk9IjI0MC4zMiIgd2lkdGg9IjQ5LjEiIGhlaWdodD0iMjAwLjA0IiBmaWxsPSIjNjhlMWZkIi8+PHJlY3QgeD0iNTIuMzUiIHk9IjI0MC4zMiIgd2lkdGg9IjQ5LjEiIGhlaWdodD0iMjAwLjA0IiBmaWxsPSIjNjhlMWZkIi8+PHJlY3QgeD0iNTIuMzUiIHk9IjI0MC4zMiIgd2lkdGg9IjQ5LjEiIGhlaWdodD0iNTUuODYiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTMpIi8+PHJlY3QgeD0iNDExLjM5IiB5PSIyNDAuMzIiIHdpZHRoPSI0OS4xIiBoZWlnaHQ9IjU1Ljg2IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC00KSIvPjxyZWN0IHg9IjM0LjE3IiB5PSIyMjMuOTUiIHdpZHRoPSI0MzcuMzciIGhlaWdodD0iMjAiIGZpbGw9IiM2OGUxZmQiLz48cGF0aCBkPSJNMjU2LjU1LDI3Ny4zN3MtNjYuMzgsMjkuMS02OS4xMSwzNC4xLTEuODIsMTcuNzMsMi4yOCwyMy4xOSw0OS4xLDg3Ljc1LDQ5LjEsODcuNzVsMTUtNC4xTDIyNC4yNywzMjkuMnM4MS44NC00LjU0LDg3Ljc1LTEwLjQ1LDE0LjA5LTIzLjY0LDE0LjA5LTIzLjY0bC00Mi43NC0zOC42NVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0iIzY4ZTFmZCIvPjxwYXRoIGQ9Ik0yNTYuNTUsMjc3LjM3cy02Ni4zOCwyOS4xLTY5LjExLDM0LjEtMS44MiwxNy43MywyLjI4LDIzLjE5LDQ5LjEsODcuNzUsNDkuMSw4Ny43NWwxNS00LjFMMjI0LjI3LDMyOS4yczgxLjg0LTQuNTQsODcuNzUtMTAuNDUsMTQuMDktMjMuNjQsMTQuMDktMjMuNjRsLTQyLjc0LTM4LjY1WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC01KSIvPjxyZWN0IHg9IjkwLjA5IiB5PSI1OS4zNyIgd2lkdGg9IjIxMy42OCIgaGVpZ2h0PSIxMzQuNTciIHJ4PSIxMC41MyIgZmlsbD0iIzY4ZTFmZCIvPjxyZWN0IHg9Ijk2LjY1IiB5PSI2NSIgd2lkdGg9IjIwMC4wMiIgaGVpZ2h0PSIxMjIuMDYiIHJ4PSI5LjciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTYpIi8+PHJlY3QgeD0iOTYuNjUiIHk9IjY1IiB3aWR0aD0iMjAwLjAyIiBoZWlnaHQ9IjEyMi4wNiIgcng9IjkuNyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtNykiLz48cGF0aCBkPSJNMjcxLjIxLDEyMi41MmMtNSw5LTEyLDE2LjcyLTE2LjY1LDI1LjktMy4zNyw2LjcxLTUuMzcsMTQtOC40MSwyMC44OHMtNy4zOSwxMy41NC0xNCwxNy4xNmMtMi42OSwxLjQ4LTUuOSwyLjYyLTcuMjksNS4zNWEyNTAuNjksMjUwLjY5LDAsMCwwLDQyLjU3LDMsNi4zMyw2LjMzLDAsMCwwLDIuNjctLjQzLDYuNzcsNi43NywwLDAsMCwyLjM4LTIuNDZjOS42OC0xMy44NiwyNS42OS0yMy44MywzMC4zOC00MC4wNywyLjE3LTcuNDcsMS42MS0xNS40MywxLTIzLjE5LS43NC0xMC4xNS0xLjQ5LTIwLjMyLTMtMzAuNC0xLjEyLTcuNjEtMS45My0xNS44OC0xMC0xOS4xMS00LjY1LTEuODctMTEuMTctMi0xNS41NC43NC02LjA1LDMuNzMtMy4xMyw4LS44MiwxMy4xOUMyNzksMTAyLjc1LDI3Ni4xOCwxMTMuNjUsMjcxLjIxLDEyMi41MloiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtOCkiLz48cGF0aCBkPSJNMjk5LjQ0LDEyMC4zOGExLjI2LDEuMjYsMCwwLDEsLjg0LjE1LDEuMTYsMS4xNiwwLDAsMSwuMy42NCwzNC4yOCwzNC4yOCwwLDAsMSwuMyw0LjU0LDYuNzEsNi43MSwwLDAsMCwxLjUxLDQuMTljMS41LDEuNTksMy45MywxLjc0LDYuMTEsMS44YTQuNDksNC40OSwwLDAsMCwxLjM3LS4xMSw4Ljc4LDguNzgsMCwwLDAsMS42OS0xYzEuNTUtLjg5LDMuNTEtLjc0LDUuMS0xLjU1YTYuMzMsNi4zMywwLDAsMCwxLjY0LTEuMjdjMy4xNS0zLjMsMy40NC04LjQ3LDIuMzgtMTIuOTJzLTMuMjEtOC41Ni00LjM3LTEzYy0xLTMuOTEtMS4yOC04LjE3LTMuNTMtMTEuNTNhMi43NiwyLjc2LDAsMCwwLTIuMTEtMS40Niw0My44NSw0My44NSwwLDAsMC0xMC4xOC0uNjFjLTIuNzQsMC01LjYuMTUtOCwxLjQ2LTEuNTQuODMtNS44NC01LjczLTYuOTItNC4zNi0uNzYsMSwxLjA1LDIxLjYxLDEuMywyMy4yQzI4OSwxMjIsMjk1LjY3LDEyMC41NywyOTkuNDQsMTIwLjM4WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC05KSIvPjxwYXRoIGQ9Ik0yNjguMTQsMTU5LjE3czcuMjgtMjUuOTIsMjIuNTEtMzAuNjksMzguMTktNi4xNCw0My40Mi00Ljc4LDIwLjIzLDkuNzgsMjEuODIsMzMuODgsMi45NSwzNi4xNCwyLjk1LDM2LjE0bC00LjA5LDEwMS4zOXMtNTUuOTIsOS4wOS03MC45MiwyLjI3bC01LjQ2LTI1LTUuNDUsMTkuNTUtMTYuMzctMTQuNTUsOS4wOS0zMC40NlMyNjQuMjgsMTc0LjE3LDI2OC4xNCwxNTkuMTdaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIGZpbGw9IiM2OGUxZmQiLz48cGF0aCBkPSJNMjY4LjE0LDE1OS4xN3M3LjI4LTI1LjkyLDIyLjUxLTMwLjY5LDM4LjE5LTYuMTQsNDMuNDItNC43OCwyMC4yMyw5Ljc4LDIxLjgyLDMzLjg4LDIuOTUsMzYuMTQsMi45NSwzNi4xNGwtNC4wOSwxMDEuMzlzLTU1LjkyLDkuMDktNzAuOTIsMi4yN2wtNS40Ni0yNS01LjQ1LDE5LjU1LTE2LjM3LTE0LjU1LDkuMDktMzAuNDZTMjY0LjI4LDE3NC4xNywyNjguMTQsMTU5LjE3WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xMCkiLz48cGF0aCBkPSJNMzI2LjY5LDE5NGMtMy42OSw2LjEtNS4zOCwxMy4xNi03LDIwLjA4TDMwOS4wNiwyNTljLTIuMjEsOS4zNi00LjQ3LDE4Ljg2LTkuMDYsMjcuMzFzLTExLjg3LDE1LjkxLTIxLjEyLDE4LjU1Yy02Ljg2LDItMTQuMTgsMS4xNy0yMS4yNywxLjk1YTQ4LjQzLDQ4LjQzLDAsMCwwLTM1LjExLDIyLDYzNC4xNCw2MzQuMTQsMCwwLDAsODcuNTUtNC45YzQuMjktLjU0LDguNzMtMS4xOCwxMi4zOS0zLjQ5LDQuMjktMi43Miw2LjkzLTcuMzgsOS0xMiw0LjUxLTkuODgsNy40MS0yMC40MSwxMC0zMWE1MjUuMSw1MjUuMSwwLDAsMCw5LjkyLTUyLjYzYzIuMi0xNi4xMyw2LjY5LTM2LjMxLDMuOTMtNTIuMzRDMzQ0LjcyLDE3NC44MywzMzIuMzEsMTg0Ljc2LDMyNi42OSwxOTRaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIG9wYWNpdHk9IjAuNDgiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTExKSIvPjxwb2x5Z29uIHBvaW50cz0iMjM2Ljg4IDIyMSAyNjMuMDggMjIwLjc3IDI2My43NiAyMDguNzIgMjM2Ljg4IDIyMSIgZmlsbD0ibm9uZSIgc3Ryb2tlPSIjM2NiNmQ1IiBzdHJva2UtbWl0ZXJsaW1pdD0iMTAiIHN0cm9rZS13aWR0aD0iMS4yOCIvPjxwb2x5Z29uIHBvaW50cz0iMjUzLjMxIDMyMi42MSAzMDcuODYgNDE0LjQ1IDMxOS42OCA0MTEuNzIgMjkyLjQgMzE5LjQzIDI1My4zMSAzMjIuNjEiIGZpbGw9IiM2OGUxZmQiLz48cG9seWdvbiBwb2ludHM9IjI1My4zMSAzMjIuNjEgMzA3Ljg2IDQxNC40NSAzMTkuNjggNDExLjcyIDI5Mi40IDMxOS40MyAyNTMuMzEgMzIyLjYxIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xMikiLz48cGF0aCBkPSJNNDI1LjIzLDIyOS42NGMtMi4yOCw5LjExLTIxLjg1LDg1LTIxLjg1LDg1cy01LDIwLjkyLTIwLjQ0LDIwLjkyYy04LjI5LDAtNDguODgtLjcyLTg0LjczLTEuNC0zMS0uNTgtNTguNDctMS4xMi01OC40Ny0xLjEycy0zLjYzLTEzLjQxLDcuNzEtMTQuMzQsNDMuNjQsMCw0My42NCwwLDE1Ljk0LS44NywyMi4yOS0xNi44YzUuMjMtMTMsMTcuMTQtNjUuNzksMjEuMzEtODQuMzlhMzQsMzQsMCwwLDEsNi41OS0xMy45YzcuMTctOS4xNiwyMS40MS0yMy42OSw0MC4zLTI0LjksMTkuNjItMS4zMSwzMi4yMiw2LjA1LDM4LjcxLDEyLjU5YTIyLjA5LDIyLjA5LDAsMCwxLDQuOTQsNi45M0M0MjcuNSwyMDQuMTYsNDI3LjUsMjIwLjUzLDQyNS4yMywyMjkuNjRaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIGZpbGw9IiM2OGUxZmQiLz48cGF0aCBkPSJNNDIwLjI5LDE5MS4zMmMwLC41OCwwLDEuMTItLjA1LDEuNywwLDAtMzguMjItMTMuNjEtNjYuODUsMjkuMzVsLTI2LjYsOTMuNHMtNS4yOCwxNy43My0yOC41OCwxOC40MWMtMzEtLjU4LTU4LjQ3LTEuMTItNTguNDctMS4xMnMtMy42My0xMy40MSw3LjcxLTE0LjM0LDQzLjY0LDAsNDMuNjQsMCwxNS45NC0uODcsMjIuMjktMTYuOGM1LjIzLTEzLDE3LjE0LTY1Ljc5LDIxLjMxLTg0LjM5YTM0LDM0LDAsMCwxLDYuNTktMTMuOWM3LjE3LTkuMTYsMjEuNDEtMjMuNjksNDAuMy0yNC45QzQwMS4yLDE3Ny40Miw0MTMuOCwxODQuNzgsNDIwLjI5LDE5MS4zMloiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTMpIi8+PHJlY3QgeD0iMzExLjk1IiB5PSIzMjguMzMiIHdpZHRoPSI3LjI3IiBoZWlnaHQ9IjExMi40OSIgZmlsbD0iIzY4ZTFmZCIvPjxyZWN0IHg9IjMxMS45NSIgeT0iMzI4LjMzIiB3aWR0aD0iNy4yNyIgaGVpZ2h0PSIxMTIuNDkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTE0KSIvPjxsaW5lIHgxPSIzMTEuOTUiIHkxPSI0NDAuODIiIHgyPSIzMTEuOTUiIHkyPSIzMjguMzMiIGZpbGw9IiM2OGUxZmQiIG9wYWNpdHk9IjAuMTgiIHN0eWxlPSJpc29sYXRpb246aXNvbGF0ZSIvPjxyZWN0IHg9IjI4Ni44MyIgeT0iNDMxLjkzIiB3aWR0aD0iNjEuMzgiIGhlaWdodD0iOSIgcng9IjQuNSIgZmlsbD0iIzY4ZTFmZCIvPjxyZWN0IHg9IjI4Ni44MyIgeT0iNDMxLjkzIiB3aWR0aD0iNjEuMzgiIGhlaWdodD0iOSIgcng9IjQuNSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTUpIi8+PHJlY3QgeD0iMTcwLjc5IiB5PSIxOTMuODgiIHdpZHRoPSI2Mi4wNiIgaGVpZ2h0PSIyNS42OSIgZmlsbD0iIzY4ZTFmZCIvPjxyZWN0IHg9IjE3MC43OSIgeT0iMTkzLjg4IiB3aWR0aD0iNjIuMDYiIGhlaWdodD0iMjUuNjkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTE2KSIvPjxyZWN0IHg9IjE0Mi43MyIgeT0iMjEyLjk3IiB3aWR0aD0iMTEzLjY2IiBoZWlnaHQ9IjEwLjkxIiBmaWxsPSIjNjhlMWZkIi8+PHJlY3QgeD0iMTQ0LjUyIiB5PSIyMTMuNzciIHdpZHRoPSIxMTMuNjYiIGhlaWdodD0iOC41NSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTcpIi8+PHBhdGggZD0iTTI5Ny41NCw2OC4wN2MtMS44OCwxLjQtMy41MSwzLjEzLTUuNDksNC4zOGExNy42NywxNy42NywwLDAsMS05LDIuNDhjLTIuMTUuMDctNC43OC4xLTUuODEsMi0uODUsMS41NSwwLDMuNTEsMS4wOCw0Ljg5QTEyLjYsMTIuNiwwLDAsMCwyODIsODQuOWE4LjcsOC43LDAsMCwxLDIsMS4yOGMxLjIzLDEuMjUsMS4yNCwzLjIzLDIsNC44MSwxLjA4LDIuMjIsMy41NCwzLjQsNS4xMiw1LjMsMy4xMSwzLjczLDIuMzUsOS40OSw1LDEzLjUzYTEzLjU3LDEzLjU3LDAsMCwwLDYuMzUsNC43QTIwLjIsMjAuMiwwLDAsMCwzMTMuMywxMTZhMTQuMTEsMTQuMTEsMCwwLDAsOS4yNC01LjQzYzEuODktMi42MywyLjY1LTUuODksMy4xOS05LjA4LDEuMDctNi4yOSwxLjQ0LTEyLjgyLS4xNC0xOUMzMjIuNDcsNzAuMzQsMzA5LjYxLDU5LjEsMjk3LjU0LDY4LjA3WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSIjM2YzZDU2Ii8+PHBhdGggZD0iTTI5Ny41NCw2OC4wN2MtMS44OCwxLjQtMy41MSwzLjEzLTUuNDksNC4zOGExNy42NywxNy42NywwLDAsMS05LDIuNDhjLTIuMTUuMDctNC43OC4xLTUuODEsMi0uODUsMS41NSwwLDMuNTEsMS4wOCw0Ljg5QTEyLjYsMTIuNiwwLDAsMCwyODIsODQuOWE4LjcsOC43LDAsMCwxLDIsMS4yOGMxLjIzLDEuMjUsMS4yNCwzLjIzLDIsNC44MSwxLjA4LDIuMjIsMy41NCwzLjQsNS4xMiw1LjMsMy4xMSwzLjczLDIuMzUsOS40OSw1LDEzLjUzYTEzLjU3LDEzLjU3LDAsMCwwLDYuMzUsNC43QTIwLjIsMjAuMiwwLDAsMCwzMTMuMywxMTZhMTQuMTEsMTQuMTEsMCwwLDAsOS4yNC01LjQzYzEuODktMi42MywyLjY1LTUuODksMy4xOS05LjA4LDEuMDctNi4yOSwxLjQ0LTEyLjgyLS4xNC0xOUMzMjIuNDcsNzAuMzQsMzA5LjYxLDU5LjEsMjk3LjU0LDY4LjA3WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0xOCkiLz48cGF0aCBkPSJNMzAwLjcyLDEzOC4zMWExNS42MywxNS42MywwLDAsMSwyLjQ2LDEyLjg4Yy0yLjYyLDExLjM3LTkuODcsMzguMzUtMjIuMDgsNTAtMTUuNjksMTUtMzkuNTUsMzAuNjktODksMjkuMzNsLjY5LTEzLjY0czUzLjUzLTQuNzgsNTguMy0yMi41MSwyMy41My01NS45MiwzMC4zNS01OS42N0MyODYuOCwxMzEuNzgsMjk1LjMzLDEzMS4xNSwzMDAuNzIsMTM4LjMxWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSIjNjhlMWZkIi8+PHBhdGggZD0iTTMwMC43MiwxMzguMzFhMTUuNjMsMTUuNjMsMCwwLDEsMi40NiwxMi44OGMtMi42MiwxMS4zNy05Ljg3LDM4LjM1LTIyLjA4LDUwLTE1LjY5LDE1LTM5LjU1LDMwLjY5LTg5LDI5LjMzbC42OS0xMy42NHM1My41My00Ljc4LDU4LjMtMjIuNTEsMjMuNTMtNTUuOTIsMzAuMzUtNTkuNjdDMjg2LjgsMTMxLjc4LDI5NS4zMywxMzEuMTUsMzAwLjcyLDEzOC4zMVoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMTkpIi8+PHBhdGggZD0iTTE4MS42MSwyMTYuMThBMjMuMjQsMjMuMjQsMCwwLDAsMTU5LjQ5LDIyNGwxMS44NSwxLjE2YTQuNDcsNC40NywwLDAsMSwyLjE5LjYsMjAuNiwyMC42LDAsMCwxLDEuNDUsMS41LDUuNjEsNS42MSwwLDAsMCwzLjUsMWMzLjcxLjE3LDcuNDMuMTgsMTEuMTQsMGEyLjA5LDIuMDksMCwwLDAsMS4zLS4zNSwyLDIsMCwwLDAsLjU1LTEuMDljLjQ5LTEuOSwxLjU3LTcuMjItLjI3LTguNTUtLjg2LS42MS0zLjUtLjUzLTQuNjEtLjgyQzE4NC45MywyMTcuMDcsMTgzLjMsMjE2LjUyLDE4MS42MSwyMTYuMThaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTIwKSIvPjxwYXRoIGQ9Ik00NDIuNyw1Ny42M3Y0Ni40NWE5LjI5LDkuMjksMCwwLDEtOS4yOSw5LjI4SDM5OS4zM2wtMTQuNDYsMjEuNTdWMTEzLjM2SDM2MS4zM2E5LjI4LDkuMjgsMCwwLDEtOS4yOS05LjI4VjU3LjYzYTkuMjgsOS4yOCwwLDAsMSw5LjI5LTkuMjhoNzIuMDhBOS4yOSw5LjI5LDAsMCwxLDQ0Mi43LDU3LjYzWiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTEuNDMgLTYuMTQpIiBmaWxsPSIjNjhlMWZkIiBvcGFjaXR5PSIwLjE4IiBzdHlsZT0iaXNvbGF0aW9uOmlzb2xhdGUiLz48cGF0aCBkPSJNNDM5LjExLDU1LjI0djQ2LjQ1YTkuMjgsOS4yOCwwLDAsMS05LjI5LDkuMjhIMzk1Ljc1bC0xNC40NywyMS41N1YxMTFIMzU3Ljc1YTkuMjksOS4yOSwwLDAsMS05LjMtOS4yOFY1NS4yNGE5LjI5LDkuMjksMCwwLDEsOS4zLTkuMjhoNzIuMDdBOS4yOCw5LjI4LDAsMCwxLDQzOS4xMSw1NS4yNFoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0iI2ZmZiIvPjxyZWN0IHg9IjEwOS42NCIgeT0iNzMuMDciIHdpZHRoPSI4LjQ0IiBoZWlnaHQ9IjEwNC40IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0yMSkiLz48cGF0aCBkPSJNMzc0Ljk0LDc5LjIxbDE0LjYyLTcuNTN2Mi4xOEwzNzcuMjQsODB2LjA3bDEyLjMyLDYuMTd2Mi4xOGwtMTQuNjItNy41M1oiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC0xLjQzIC02LjE0KSIgZmlsbD0iIzY4ZTFmZCIvPjxwYXRoIGQ9Ik0zOTEuNiw4OS43MWw4Ljc5LTIyLjg1aDIuMTRsLTguODIsMjIuODVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIGZpbGw9IiM2OGUxZmQiLz48cGF0aCBkPSJNNDE5LjEzLDgxbC0xNC42MSw3LjVWODYuMjdsMTIuNDEtNi4xN1Y4MGwtMTIuNDEtNi4xN1Y3MS42OGwxNC42MSw3LjVaIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgtMS40MyAtNi4xNCkiIGZpbGw9IiM2OGUxZmQiLz48cmVjdCB4PSIxMzQuMTciIHk9Ijg5LjY4IiB3aWR0aD0iMjcuMTMiIGhlaWdodD0iMS45OSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMjIpIi8+PHJlY3QgeD0iMTM0LjE3IiB5PSI5My41MyIgd2lkdGg9IjE2LjU2IiBoZWlnaHQ9IjEuODciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTIzKSIvPjxyZWN0IHg9IjE1Ny40MSIgeT0iOTMuNTMiIHdpZHRoPSI1Mi4xMSIgaGVpZ2h0PSIxLjg4IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0yNCkiLz48cmVjdCB4PSIyMTQuMzkiIHk9IjkzLjUzIiB3aWR0aD0iMjkuMzMiIGhlaWdodD0iMS44OCIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMjUpIi8+PHJlY3QgeD0iMTQyLjc4IiB5PSI5Ny4zOSIgd2lkdGg9IjIyLjc3IiBoZWlnaHQ9IjEuOTciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTI2KSIvPjxyZWN0IHg9IjE1MC4wOSIgeT0iMTAxLjI0IiB3aWR0aD0iMjcuMTMiIGhlaWdodD0iMS45OSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMjcpIi8+PHJlY3QgeD0iMTc4Ljk5IiB5PSIxMDEuMjQiIHdpZHRoPSIyMi43NCIgaGVpZ2h0PSIyLjIxIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0yOCkiLz48cmVjdCB4PSIxNTAuMDUiIHk9IjEwNS4wOSIgd2lkdGg9IjIwLjk1IiBoZWlnaHQ9IjEuODciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTI5KSIvPjxyZWN0IHg9IjIzMS41MSIgeT0iMTA1LjA5IiB3aWR0aD0iMjAuOTUiIGhlaWdodD0iMS44NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMzApIi8+PHJlY3QgeD0iMTczLjAxIiB5PSIxMDUuMDkiIHdpZHRoPSI0My4yMyIgaGVpZ2h0PSIyLjA3IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0zMSkiLz48cmVjdCB4PSIyMjAuMzUiIHk9IjEwNS4wOSIgd2lkdGg9IjkuNTMiIGhlaWdodD0iMi4xMSIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMzIpIi8+PHJlY3QgeD0iMTM0LjE3IiB5PSIxMTAuMyIgd2lkdGg9IjI3LjEzIiBoZWlnaHQ9IjEuOTkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTMzKSIvPjxyZWN0IHg9IjEzNC4xNyIgeT0iMTE0LjE1IiB3aWR0aD0iMTYuNTYiIGhlaWdodD0iMS44NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMzQpIi8+PHJlY3QgeD0iMTU3LjQxIiB5PSIxMTQuMTUiIHdpZHRoPSI1Mi4xMSIgaGVpZ2h0PSIxLjg4IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0zNSkiLz48cmVjdCB4PSIyMTQuMzkiIHk9IjExNC4xNSIgd2lkdGg9IjI5LjMzIiBoZWlnaHQ9IjEuODgiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTM2KSIvPjxyZWN0IHg9IjE0Mi43OCIgeT0iMTE4IiB3aWR0aD0iMjIuNzciIGhlaWdodD0iMS45NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtMzcpIi8+PHJlY3QgeD0iMTUwLjA5IiB5PSIxMjEuODYiIHdpZHRoPSIyNy4xMyIgaGVpZ2h0PSIxLjk5IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC0zOCkiLz48cmVjdCB4PSIxNzguOTkiIHk9IjEyMS44NiIgd2lkdGg9IjIyLjc0IiBoZWlnaHQ9IjIuMjEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTM5KSIvPjxyZWN0IHg9IjE1MC4wNSIgeT0iMTI1LjcxIiB3aWR0aD0iMjAuOTUiIGhlaWdodD0iMS44NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtNDApIi8+PHJlY3QgeD0iMjMxLjUxIiB5PSIxMjUuNzEiIHdpZHRoPSIyMC45NSIgaGVpZ2h0PSIxLjg3IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC00MSkiLz48cmVjdCB4PSIxNzMuMDEiIHk9IjEyNS43MSIgd2lkdGg9IjQzLjIzIiBoZWlnaHQ9IjIuMDciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTQyKSIvPjxyZWN0IHg9IjIyMC4zNSIgeT0iMTI1LjcxIiB3aWR0aD0iOS41MyIgaGVpZ2h0PSIyLjExIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC00MykiLz48cmVjdCB4PSIxMzQuMTciIHk9IjEzMC45MiIgd2lkdGg9IjI3LjEzIiBoZWlnaHQ9IjEuOTkiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTQ0KSIvPjxyZWN0IHg9IjEzNC4xNyIgeT0iMTM0Ljc3IiB3aWR0aD0iMTYuNTYiIGhlaWdodD0iMS44NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtNDUpIi8+PHJlY3QgeD0iMTU3LjQxIiB5PSIxMzQuNzciIHdpZHRoPSI1Mi4xMSIgaGVpZ2h0PSIxLjg4IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC00NikiLz48cmVjdCB4PSIyMTQuMzkiIHk9IjEzNC43NyIgd2lkdGg9IjI5LjMzIiBoZWlnaHQ9IjEuODgiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTQ3KSIvPjxyZWN0IHg9IjE0Mi43OCIgeT0iMTM4LjYyIiB3aWR0aD0iMjIuNzciIGhlaWdodD0iMS45NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtNDgpIi8+PHJlY3QgeD0iMTUwLjA5IiB5PSIxNDIuNDciIHdpZHRoPSIyNy4xMyIgaGVpZ2h0PSIxLjk5IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC00OSkiLz48cmVjdCB4PSIxNzguOTkiIHk9IjE0Mi40NyIgd2lkdGg9IjIyLjc0IiBoZWlnaHQ9IjIuMjEiIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTUwKSIvPjxyZWN0IHg9IjE1MC4wNSIgeT0iMTQ2LjMzIiB3aWR0aD0iMjAuOTUiIGhlaWdodD0iMS44NyIgZmlsbD0idXJsKCNsaW5lYXItZ3JhZGllbnQtNTEpIi8+PHJlY3QgeD0iMjMxLjUxIiB5PSIxNDYuMzMiIHdpZHRoPSIyMC45NSIgaGVpZ2h0PSIxLjg3IiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC01MikiLz48cmVjdCB4PSIxNzMuMDEiIHk9IjE0Ni4zMyIgd2lkdGg9IjQzLjIzIiBoZWlnaHQ9IjIuMDciIGZpbGw9InVybCgjbGluZWFyLWdyYWRpZW50LTUzKSIvPjxyZWN0IHg9IjIyMC4zNSIgeT0iMTQ2LjMzIiB3aWR0aD0iOS41MyIgaGVpZ2h0PSIyLjExIiBmaWxsPSJ1cmwoI2xpbmVhci1ncmFkaWVudC01NCkiLz48L3N2Zz4=');
        background-repeat: no-repeat;
        display: flex;
        padding: 150px 100px;
        overflow: hidden;
        padding-bottom: 15px;
        opacity: 1;
    }
    .sponsor h2.slogan {
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
    .sponsor-list {
        width: 50%;
        color: #666;
    }
    .sponsor-item .list {
        display: inline-block;
        height: auto;
        width: 120px;
        margin-right: 30px;
    }
    .sponsor-item h3, .sponsor-detail h3 {
        text-align: center;
        font-size: 30px;
        margin-bottom: 25px;
        font-weight: 100;
    }
    .sponsor-detail {
        width: 50%;
        color: #666;
    }
    .sponsor-detail p a {
        display: inline;
        color:rgba(34, 181, 111, 1);
        text-decoration: underline;
    }
    .sponsor-detail p {
        margin-bottom: 20px;
        margin-top: 30px;
        font-size: 16px;
    }
    @media screen and (max-width: 1063px){
      .sponsor-detail p {
        font-size: 13px;
      }
    }
    .detail-link {
        display: flex;
        align-items: center;
    }
    .detail-link img {
        margin: 0 4px;
    }
    .d-flex {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-around;
        padding: 5px 0;
        margin-bottom: 30px;
    }
    a.detail-link {
        color: #fff;
    }
    a.detail-link:first-of-type {
        border: 1px solid #666;
        border-radius: 9999px;
        background: #fff;
        padding: 6px 8px;
    }
    a.detail-link:last-of-type {
        border: 1px solid #f96854;
        background: #f96854;
        border-radius: 5px;
        padding: 6px 8px;
    }
    @media screen and (max-width: 950px){
        .sponsor {
            height: auto;
            padding: 20px;
            overflow: auto;
            flex-direction: column;
        }
        .sponsor h2.slogan {
            position: relative;
            left: auto;
            top: auto;
            transform: none;
            max-width: 200px;
            margin: 0 auto 30px;
            text-align: center;
        }
        .sponsor-list,.sponsor-detail {
            width: 100%;
        }
        .sponsor-item {
            margin-bottom: 25px;
        }
    }
</style>

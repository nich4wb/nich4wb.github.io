blog {
    display: flex;
    justify-content: space-between;
    margin-top: 50px;
}
.blog__sidebar {
    width: 195px;
    margin-bottom: 35px;
}
.blog__main {
    width: 740px;
    margin-bottom: 35px;
}
.sidebar__menu {
    margin-top: 40px;
    margin-bottom: 50px;
}
.sidebar__item {
    margin-bottom: 5px;
}
.sidebar__link,
.sidebar__link:active{
    font-family: 'SpaceGrotesk';
    font-size: 20px;
    line-height: 1.77em;
    font-weight: bold;
    color: #BFCDD6;
    transition: all 0.2s;
}
.sidebar__link:hover {
    color: #3E4FEA;
}
.sidebar__link:focus {
    color: #2632A3;
}
.sidebar__link.active {
    color: #000;
    border-bottom: 3px solid #3E4FEA;
    pointer-events: none;
}
.sidebar__form-title {
    font-family: 'SpaceGrotesk';
    font-size: 20px;
    font-weight: bold;
    margin-bottom: 15px;
}
.sidebar__form-continue {
    font-size: 14px;
    color: #6A737D;
    margin-top: 20px;
    margin-bottom: 10px;
}
.sidebar__button-group .button {
    width: 100%;
    margin-bottom: 10px;
    padding: 15px 20px;
    font-size: 16px;
}
.sidebar__button-group .button .icon_facebook {
    width: 19px;
    height: 21px;
    background-size: 11px;
    margin-right: 10px;
}
.sidebar__button-group .button .icon_google {
    width: 19px;
    height: 19px;
    background-size: 19px;
    margin-right: 10px;
}
.sidebar__form-agreement {
    font-size: 10px;
    line-height: 13px;
    color: #6A737D;
    margin-top: 20px;
    text-align: center;
}
.sidebar__form-agreement a {
    text-decoration: underline;
}
.sidebar__form-agreement a:hover {
    text-decoration: none;
}

.blog__list {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    margin-top: 80px;
}
.blog__item {
    width: 336px;
    margin-bottom: 50px;
    position: relative;
}
.blog__category {
    position: absolute;
    top: 0;
    left: 0;
    padding: 5px 8px;
    background-color: #000;
    color: #fff;
    font-size: 14px;
    line-height: 1.36;
    border-top-left-radius: 10px;
    border-bottom-right-radius: 10px;
}
.blog__post-content img:not([data-no-style='true']),
.blog__img {
    width: 100%;
    border-radius: 20px;
    margin-bottom: 20px;
    box-shadow: 20px 20px 40px 0 rgba(90, 117, 157, 0.11)
}
.blog__category ~ .blog__img {
    border-top-left-radius: 10px;
}
.blog__date {
    font-size: 12px;
    line-height: 1em;
    color: #6A737D;
    margin-bottom: 10px;
}
.blog__post-title {
    font-family: 'SpaceGrotesk';
    font-size: 18px;
    font-weight: bold;
    line-height: 1.36em;
}
.blog__post-content {
    margin-bottom: 50px;
}
.blog__post-content iframe {
    box-shadow: 20px 20px 40px 0 rgba(90, 117, 157, 0.11);
    border-radius: 20px;
}
.blog__latest-post{
    position: relative;
}
.blog__latest-post-title {
    font-family: 'SpaceGrotesk';
    font-size: 38px;
    font-weight: bold;
    line-height: 1.38em;
}
.blog__data {
    display: flex;
    align-items: center;
    margin-top: 20px;
    flex-wrap: wrap;
    position: relative;
}
.blog__author {
    display: flex;
    align-items: center;
    margin-bottom: 10px;
}
.blog__author:after {
    content: '';
    display: inline-block;
    width: 4px;
    height: 4px;
    background-color: #6A737D;
    border-radius: 50%;
    opacity: 0.7;
    margin-right: 7px;
}
.blog__author-data {
    display: flex;
    align-items: center;
    margin-bottom: 25px;
}
.blog__author-img {
    width: 25px;
    border-radius: 50%;
    margin-right: 10px;
}
.blog__author-img--big {
    width: 70px;
    border-radius: 50%;
    margin-right: 10px;
}
.blog__author-name {
    color: #6A737D;
    font-size: 12px;
    line-height: 1.36em;
    margin-right: 7px;
}
.blog__author-name--big {
    color: #000;
    font-size: 20px;
    font-weight: 500;
    line-height: 1.36em;
}
.blog__author-career {
    font-size: 14px;
    line-height: 1.81;
    color: #6A737D;
}
.blog__author-description {
    font-size: 18px;
    line-height: 26px;
    color: #6A737D;
    margin-bottom: 70px;
}
.blog__reading-time {
    color: #6A737D;
    font-size: 12px;
    line-height: 1.36em;
    opacity: 0.7;
    margin-right: auto;
    margin-bottom: 10px;
}
.blog__share {
    margin-bottom: 10px;
}

.blog__arrow-top {
    background: url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTkiIGhlaWdodD0iNzgiIHZpZXdCb3g9IjAgMCA1OSA3OCIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4NCjxwYXRoIGQ9Ik0zMC4yNSA2NS41MDI1QzMwLjI1IDY2LjE5MjkgMjkuNjkwNCA2Ni43NTI1IDI5IDY2Ljc1MjVDMjguMzA5NiA2Ni43NTI1IDI3Ljc1IDY2LjE5MjkgMjcuNzUgNjUuNTAyNUwzMC4yNSA2NS41MDI1Wk0yOC4xMTYxIDAuNjE4NjUyQzI4LjYwNDMgMC4xMzA0OTMgMjkuMzk1NyAwLjEzMDQ5MyAyOS44ODM5IDAuNjE4NjUyTDM3LjgzODggOC41NzM2QzM4LjMyNyA5LjA2MTc2IDM4LjMyNyA5Ljg1MzIxIDM3LjgzODggMTAuMzQxNEMzNy4zNTA3IDEwLjgyOTUgMzYuNTU5MiAxMC44Mjk1IDM2LjA3MTEgMTAuMzQxNEwyOSAzLjI3MDNMMjEuOTI4OSAxMC4zNDE0QzIxLjQ0MDggMTAuODI5NSAyMC42NDkzIDEwLjgyOTUgMjAuMTYxMiAxMC4zNDE0QzE5LjY3MyA5Ljg1MzIxIDE5LjY3MyA5LjA2MTc2IDIwLjE2MTIgOC41NzM2TDI4LjExNjEgMC42MTg2NTJaTTI3Ljc1IDY1LjUwMjVMMjcuNzUgMS41MDI1NEwzMC4yNSAxLjUwMjU0TDMwLjI1IDY1LjUwMjVMMjcuNzUgNjUuNTAyNVoiIGZpbGw9ImJsYWNrIi8+DQo8L3N2Zz4NCg==') center no-repeat;
    width: 58px;
    height: 76px;
    display: inline-block;
    margin-bottom: 100px;
    position: absolute;
    bottom: 0;
    left: 237px;
    cursor: pointer;
    transition: all 0.4s;
}
.blog__arrow-top:hover {
    transform: translateY(-7px);
}
.blog__arrow-top--post {
    left: -60px;
    bottom: 100px;
}

.author {
    margin-bottom: 70px;
}
.author__data {
    display: flex;
    align-items: flex-end;
    margin-bottom: 25px;
}
.author__img {
    border-radius: 20px;
    margin-right: 25px;
    width: 120px;
    height: 120px;
    align-self: flex-start;
}
.author__name {
    font-family: 'SpaceGrotesk';
    font-size: 70px;
    line-height: 1.17;
}
.author__career {
    color: #6A737D;
    font-size: 14px;
    margin-bottom: 5px;
}
.author__description {
    color: #6A737D;
    font-size: 18px;
}
.author__post-list {
    width: 720px;
}
.author__post {
    width: 336px;
    margin-bottom: 50px;
    position: relative;
}


.blog-progress-bar {
    width: 100%;
    pointer-events: none;
    -webkit-appearance: none;
    -moz-appearance: none;
    appearance: none;
    max-height: 3px;
    position: absolute;
}
.blog-progress-bar {
    color: #3E4FEA;
}
.blog-progress-bar::-moz-progress-bar {
    background: #3E4FEA;
}
.blog-progress-bar::-webkit-progress-value {
    background: #3E4FEA;
}
.blog-progress-bar::-webkit-progress-bar {
    background: transparent;
}

.post {
    padding-top: 30px;
}
.post p {
    color: #6A737D;
    margin-bottom: 25px;
    font-weight: 300;
}
.post b, .post strong {
    font-weight: 500;
}
.post h1 {
    font-size: 38px;
    line-height: 1.36;
}
.post h2 {
    font-size: 32px;
}
.post h3 {
    font-size: 26px;
}
.post h4 {
    font-size: 18px;
    font-weight: 600;
    color: #6A737D;
}
.post h2, .post h3, .post h4, .post h5, .post h6 {
    margin: 50px 0 25px;
    line-height: 1.36;
}
.post ul,
.post ul:not(.ya-share2__list) {
    list-style-type: none;
    margin-bottom: 25px;
}
.post ol,
.post ol:not(.ya-share2__list)  {
    list-style-type: decimal;
    margin-bottom: 25px;
    padding-left: 25px;
}
.post ul > li:not(.ya-share2__item):before {
    content: '';
    background-color: #6A737D;
    min-width: 7px;
    height: 7px;
    border-radius: 50%;
    display: inline-block;
    margin-right: 20px;
    position: relative;
    top: -4px;
    left: 3px;
}
.post li:not(.ya-share2__item) {
    color: #6A737D;
    margin-bottom: 5px;
}
.post ul > li:last-child,
.post li:last-child:not(.ya-share2__item) {
    margin-bottom: 0;
}
.post ul > ul {
    padding-left: 30px;
    margin-top: 20px;
}

.post ul > ol {
    padding-left: 55px !important;
    margin-top: 20px;
}
.post blockquote {
    font-family: 'SpaceGrotesk';
    font-size: 38px;
    line-height: 1.36;
    font-weight: bold;
    border-left: 4px solid #3E4FEA;
    padding: 20px 40px;
    margin: 50px 0;
}
.post blockquote:before {
    content: '“';
}
.post blockquote:after {
    content: '”';
}
.post a:not(.button) {
    color: #3E4FEA;
    transition: all 0.2s;
}
.post a:not(.button):hover {
    color: #000;
}
.post__img {
    width: 100%;
}
.post__title {
    font-size: 38px;
    line-height: 1.36;
}
.post__blue-field {
    padding: 50px 75px;
    border-radius: 10px;
    background: linear-gradient(180deg, #A9B1FF -110.08%, #3E4FEA 106.37%), #FFFFFF;
    color: #fff !important;
    margin: 0 -35px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    font-size: 23px;
    line-height: 1.36;
}
.post__blue-field span {
    margin-right: 30px;
    font-size: 23px;
}
.post__blue-field .button {
    margin-left: 30px;
}
.post__share {
    position: absolute;
    left: -50px;
    top: 34px;
}
.post__share .social-networks-share,
.post__share .ya-share2__list {
    display: flex;
    flex-direction: column;
}
.post__share .ya-share2__item {
    margin-bottom: 7px !important;
    transition: all 0.2s;
}
.post__share .social-networks-share a{
    transition: all 0.2s;
}
.post__share .social-networks-share a:hover,
.post__share .ya-share2__item:hover {
    transform: translateX(10px);
}

.post__share.fixed {
    position: fixed;
    left: 20px;
    top: 50%;
    margin-top: -80px;
    z-index: 1;
}
.post__share.fixed .ya-share2__item {
    margin-bottom: 30px !important;
    transform: scale(2);
    opacity: 0.4 !important;
}
.post__share.fixed .social-networks-share {
    gap: 27px;
}
.post__share.fixed .social-networks-share a {
    transform: scale(2);
    opacity: 0.4 !important;
}
.post__share.fixed .social-networks-share a:hover,
.post__share.fixed .ya-share2__item:hover {
    opacity: 1 !important;
    transform: scale(2) translateX(10px);
}

.disqus {
    padding-bottom: 80px;
}

.pagination {
    display: flex;
    align-items: center;
    justify-content: center;
}
.pagination li {
    margin: 0 6px;
}
.pagination li a {
    padding: 6px 12px;
    border-radius: 8px;
    font-size: 16px;
    font-weight: 500;
    line-height: 1;
    color: #6A737D;
    transition: all 0.3s;
    cursor: pointer;
}
.pagination li:first-child {
    margin-left: 0;
}
.pagination li:last-child {
    margin-right: 0;
}
.pagination li.active a ,
.pagination li:not(.disabled) a:hover {
    background-color: #fff;
    color: #000;
}
.pagination li.disabled a {
    opacity: 0.3;
    cursor: not-allowed;
}
.pagination .prev a,
.pagination .next a {
    display: flex;
    align-items: center;
}
.pagination .prev a:before {
    content: '';
    border: solid #6A737D;
    border-width: 0 2px 2px 0;
    display: inline-block;
    padding: 3px;
    margin-right: 5px;
    transform: rotate(135deg);
    -webkit-transform: rotate(135deg);
}
.pagination .next a:after {
    content: '';
    border: solid #6A737D;
    border-width: 0 2px 2px 0;
    display: inline-block;
    padding: 3px;
    margin-left: 5px;
    transform: rotate(-45deg);
    -webkit-transform: rotate(-45deg);
}

.title__recommended{
    margin: 50px 0 20px;
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 10px;
}

@media screen and (max-width: $breakpoint-1200-max) {
    .blog__main {
        width: 336px;
    }
    .latest-post {
        display: none;
    }
    .blog__list {
        margin-top: 0;
    }
    .blog__post {
        width: 100%;
    }
    .blog__arrow-top {
        left: 275px;
    }
    .blog__arrow-top--post {
        left: -60px;
    }
    .author__post {
        margin-top: 30px;
    }
}
@media screen and (max-width: $breakpoint-992-max) {
    .blog__arrow-top--post {
        display: none;
    }
}
@media screen and (max-width: $breakpoint-768-max) {
    .blog__item{
        width: calc(50% - 20px);
    }
    .blog__main {
        width: 100%;
    }
    .author__post-list {
        width: 100%;
    }
    .post blockquote {
        font-size: 26px;
        padding: 20px 30px;
        margin: 50px 0;
    }
    .post__blue-field {
        flex-direction: column;
        justify-content: center;
        text-align: center;
    }
    .post__blue-field .button {
        margin-left: 0;
        margin-top: 30px;
    }
    .blog {
        flex-direction: column;
    }
    .blog__sidebar {
        width: 100%;
        text-align: center;
    }
    .sidebar__form-title {
        display: none;
    }
    .blog__main {
        padding-left: 0;
        margin-top: 50px;
    }
    .blog__arrow-top {
        display: none;
    }
    .post__blue-field {
        margin: 0;
       padding: 55px 12px;
    }
    .author__data {
        flex-direction: column;
        align-items: flex-start;
    }
    .author__img {
        margin-bottom: 20px;
    }
    .author__name {
        font-size: 32px;
    }
}
@media screen and (max-width: $breakpoint-568-max) {
    .blog img[alt="emoji flame"]{
        width: 20px;
        height: auto;
    }
}
@media screen and (max-width: $breakpoint-435-max) {
    .blog__item{
        width: 100%;
    }
}

# goit-markup-hw-04

/* -------Проэкты------- */
.projects-section {
	display: flex;
	flex-wrap: wrap;

	margin-top: calc(-1 * var(--item-gap));
	margin-left: calc(-1 * var(--item-gap));
}
.project-item {
	margin-top: var(--item-gap);
	margin-left: var(--item-gap);

	flex-basis: calc((100% - var(--item-gap) * 3) / 3);
}

.project-link {
}
.project-link:hover .project-thumb::before,
.project-link:hover .project-thumb:focus::before {
	opacity: 1;
}
.project-thumb {
	position: relative;
}
.project-thumb:before {
	content: "";
	display: inline-block;
	position: absolute;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	background: rgba(33, 150, 243, 0.9);

	opacity: 0;
}
.project-content {
	padding-top: 20px;
	padding-bottom: 20px;
	padding-left: 24px;
	padding-right: 24px;

	border-left: 1px solid #eeeeee;
	border-bottom: 1px solid #eeeeee;
	border-right: 1px solid #eeeeee;
}
.project-title {
	font-weight: 700;
	font-size: 18px;
	line-height: 2;

	letter-spacing: 0.06em;

	color: var(--secondary-text-color);
}
.project-text {
	font-weight: 400;
	font-size: 16px;
	line-height: 1.9;

	color: var(--primery-text-color);
}
.project-description {
	position: absolute;
	display: none;
	top: 0;
	left: 0;
	width: 100%;
	height: 100%;
	font-size: 18px;
	line-height: 1.56;

	padding: 63px 24px;

	color: #fff;
}
.project-link:hover .project-description,
.project-link:focus .project-description {
	display: block;
}


<li class="project-item">
						<article>
							<a class="project-link" href="#">
								<div class="project-thumb"><img src="./images/portfolio/img.jpg" height="294" width="370"
										alt="Технокряк">
									<p class="project-description">Технокряк это современная площадка распространения
										коронавируса.
										Компании используют эту платформу для цифрового шпионажа и атак на защищённые сервера
										конкурентов.</p>
								</div>
								<div class="project-content">
									<h2 class="project-title">Технокряк</h2>
									<p class="project-text">Веб-сайт</p>

								</div>
							</a>
							</articl>
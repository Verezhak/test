 <svg class="btn-close-menu">
              <use
                href="./images/icons.svg#icon-close.svg"
                width="8"
                height="8"
              ></use>
            </svg>
 display: flex;
  flex-direction: column;
  gap: 5px;
  max-width: 1170px;
  min-width: 320px;
  maring: 0 auto;
@media (min-width: 768px) {
  .container {
    flex-direction: row;
    flex-wrap: wrap;
    gap: 10px;
  }

.element {
flex-basis: calc((100% - 10px) / 2);
}
}
@media screen and (min-width: 1024px) {
.container {
gap: 15px;
}

.element {
flex-basis: calc((100% - 30px) / 3);
}
}

.calendar-container,
.calendar,
.calendar-header,
td,
tr {
    padding: 0;
    margin: 0; 
}

.calendar-conatiner{
    border: 2px solid red;
}

.calendar{
    background-color:aliceblue;
    border-spacing: 0;
    border-collapse: collapse;
    width: 100%;
}

.calendar-header {
    border-bottom: 1px dashed red;
    font-size: 1.6em;
}

.calendar-header td {
    border-spacing: 0;
    padding-left: 5px;
}

.day,
.empty-slot,
.week-day {
    text-align: center;
    height: 40px;
}

.week-day {
    font-size: 0.8em;
}

.day{
    cursor: pointer;
    width: 24px;
    height: 24px;
    line-height: 24px;
}

.current-day {
    background-color: #0094ff;
    width: 28px;
    height: 28px;
    line-height: 28px;
    border-radius: 2%;
    color: antiquewhite
}
.month-popup div{
    padding: 0.3em;
}
.nav-month {
    position: absolute;
    top: 0.6em;
    right: 3px;
}

.prev{
}

.next {
}

.editor-year {
    max-width: 3.6em;
}

.label-month,
.label-year {
    font-size: 0.6em;
}

.label-month {
    cursor: pointer;
}

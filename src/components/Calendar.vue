<template>
<div class="calendar">
  <h1>2021/05</h1>

  <div>
    <button type="button" class="btn btn-primary">&lt;</button>
    <button type="button" class="btn btn-primary">今天</button>
    <button type="button" class="btn btn-primary">&gt;</button>
  </div>

  <table class="calendar-month table table-bordered">
    <thead>
      <tr>
        <th>週一</th>
        <th>週二</th>
        <th>週三</th>
        <th>週四</th>
        <th>週五</th>
        <th>週六</th>
        <th>週日</th>
      </tr>
    </thead>
    <tbody class="calendar-date">
      <tr>
        <td class="out-of-month">26</td>
        <td class="out-of-month">27</td>
        <td class="out-of-month">28</td>
        <td class="out-of-month">29</td>
        <td class="out-of-month">30</td>
        <td>1</td>
        <td>2</td>
      </tr>
      <tr>
        <td>3</td>
        <td>4</td>
        <td class="today">5</td>
        <td>6</td>
        <td>7</td>
        <td>8</td>
        <td>9</td>
      </tr>
      <tr>
        <td>10</td>
        <td>11</td>
        <td>12</td>
        <td>13</td>
        <td>14</td>
        <td>15</td>
        <td>16</td>
      </tr>
      <tr>
        <td>17</td>
        <td>18</td>
        <td>19</td>
        <td>20</td>
        <td>21</td>
        <td>22</td>
        <td>23</td>
      </tr>
      <tr>
        <td>24</td>
        <td>25</td>
        <td>26</td>
        <td>27</td>
        <td>28</td>
        <td>29</td>
        <td>30</td>
      </tr>
      <tr>
        <td>31</td>
        <td class="out-of-month">1</td>
        <td class="out-of-month">2</td>
        <td class="out-of-month">3</td>
        <td class="out-of-month">4</td>
        <td class="out-of-month">5</td>
        <td class="out-of-month">6</td>
      </tr>
    </tbody>
  </table>
</div>
</template>

<script>
// todo: 請完成此萬年曆，要可以切換月份、回到目前所在月份。
export default {

}
</script>

<style scoped>
.calendar {
  width: 660px;
  margin: 1rem;
}

.calendar-month {
  margin-top: 1rem;
}

.out-of-month {
  background-color: #f1f1f1;
  color: #999;
}

.today {
  background-color: #ff133e;
  color: #fff;
}

.btn:nth-child(2) {
  margin: 0 0.5em;
}
</style>

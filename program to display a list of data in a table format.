import "./styles.css";
import {useState} from 'react';

export default function App() {
  
    let list = [{fruit:"apple",
    count:3},
    {fruit:"orange",
    count:5},
    {fruit:"banana",
    count:12},
    {fruit:"guava",
    count:6},
    {fruit:"kiwi",
    count:3},
  ]

  return (
    <div className="App">
      <h1>React Assignment Day 3</h1>
      <h2>Table</h2>
      <table>
      {list.map(function(item,index){
          return (
            <tr>
              <td>{item.fruit}</td>
              <td>{item.count}</td>
            </tr>
          )
      })}
      </table>
    </div>
  );
}

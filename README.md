import { useState } from 'react'
import reactLogo from './assets/react.svg'
import viteLogo from '/vite.svg'
import './App.css'

function App() {
  const [count, setCount] = useState(0);

  return (
    <>
      <div>
        <div className='="app' />
        <h1> counter app</h1>
        <h1>count</h1>
        <div className="card" />


      </div>


      <button onClick={() => setCount((count) => count + 1)}>
        count is {count}
      </button>

      <button on onClick={() => setCount((count) => count + 1)}>increment</button>

      <button on onClick={() => setCount((count) => count - 1)}>decrement</button>

      <button on onClick={() => setCount(0)}>reset</button>

    </>
  )
}

export default App

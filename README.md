import React from 'react';
import ReactDOM from 'react-dom';
import Header from './components/Header';
import BurgerList from './components/BurgerList';

function App() {
  return (
    <>
      <Header title="My Awesome Burger Project" />
      <BurgerList />
    </>
  );
}

ReactDOM.render(<App />, document.getElementById('root'));


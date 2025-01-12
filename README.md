# fraces.css
body {
  font-family: Arial, sans-serif;
  text-align: center;
  margin: 0;
  padding: 0;
  background-image: url('web2.png'); 
  background-size: cover; 
  background-position: center; 
  background-repeat: no-repeat; 
  background-attachment: fixed; 
  background-size: cover;
  background-position: center;
  background-attachment: fixed;
}

@media (max-width: 768px) {

h1 {
  color: #ffffff;
}}

#quote-box {
  margin: 20px auto;
  padding: 20px;
  background: #100e0e;
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
  border-radius: 10px;
  max-width: 600px;
  max-width: 90%; 
  padding: 2em; 
  padding: 1em;
}

#quote {
  font-size: 1.5em;
  color: #a898d9;
}

#author {
  margin-top: 10px;
  font-size: 1.2em;
  color: #777;
}

#new-quote-btn {
  margin-top: 20px;
  padding: 10px;
  background: none;
  border: none;
  cursor: pointer;
}

#new-quote-btn img {
  width: 40px;
  height: 40px;
  
}

#new-quote-btn:hover img {
  transform: scale(1.1);
  width: 60px;
  height: 60px;

}

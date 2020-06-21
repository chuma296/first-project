# first-project
import React from "react";
import { Container, Row, Col } from "react-bootstrap";
import './Login.css';
const Login = () => {
	return (
	
  <div>
     
      <div className="container">
        <h2>Sign In</h2>

        <div className="ism-form__group">
          <label for="ism-username">Email Address</label>
            
            <div className="ism-input-holder">
              <input type="email" name="login" id="ism-email" placeholder="Email Address" />
            </div>
        </div>

      <div className="ism-form__group">
        <label for="ism-password">Password</label>
        
        <div className="ism-input-holder">
          <input type="password" name="password" id="ism-password"
          placeholder="Password" data-password-element="input"/>
        </div>
      </div>

       <div className="ism-form__group">
            <a
               href="/accounts/password-reset/"      
               class="forget"         
               >Forgot login details?
            </a>
             

           <button type="submit">
             Sign in
           </button>
        </div>

      </div>

  </div>

  
  )

  }

  export default Login;

.ism-form__group{
  margin-bottom: 2rem;
  width: 100%;
  clear: both;
  display: inline-block;
  position: relative; 
  margin-top: 0.5rem;
  font-size: 1.2rem;
  font-family: "PremierSans-Bold", Arial, "Helvetica Neue", Helvetica, sans-serif;
  font-weight: bold;
}

 .ism-form__group [type="password"]{
background: #e8e8e8;
border: none;
padding: 15px;
border-bottom: 1px solid #76766f;
width: 100%;
height: 47px;
transition: all 0.3s ease-in-out;
border-radius: 0;
}


  .ism-form__group [type="email"] {
background: #e8e8e8;
border: none;
padding: 15px;
border-bottom: 1px solid #76766f;
width: 100%;
height: 47px;
transition: all 0.3s ease-in-out;
border-radius: 0;
}

 .ism-form__group [type="submit"] {
border: none;
float: right;
color: white;
border: 1px solid;
background-color: #3d195b                                                                                                                                                                                                                                                                                                                                               ;
width: 50%
}

.forget {
  color: red;
  font-size: 1.2rem;
  font-weight: small;
}


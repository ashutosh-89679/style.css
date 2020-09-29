# style.css


body{
	margin: 0;
	padding: 0;
 
}

.row{
  margin-top: 6%;
  margin-bottom: 6%;
}

h1 {
  margin-bottom: 17px;
  text-align: center;
  color:Red;
  font-size: 50px;
   font-family: areial;
}


.box{
  width: 100%;
  overflow: none;
}


.content-name{
  overflow: none;
  text-align: center;
  border: 5px solid black;
  width: 100px;
  height: 40px;
  padding: 4px;
  float: right;
  margin-right: 10px;
  margin-top: 0px;
  font-weight: bold;
  position: relative;
}

.content{
  border: 3px solid black;
  width: 90%;
  height: auto;
  margin: 2.5%;
  color: black
  font-size: 25px;
  padding: 2%;
  padding-top: 55px;
  background-color: red;
}

.name1{

  background-color:lightblue;
}

.name2{

  background-color:purple;
}
.name3{
  background-color:orange;
}



@media (min-width: 992px) {
  .col-lg-4 {
  	float: left;
    width: 33.33%;
  }
}

@media (min-width: 768px) and (max-width: 991px) {
  .col-md-6,.col-md-12 {
    float: left;
  }
  .col-md-6 {
    width: 50%;
  }
  .col-md-12 {
    margin-left: -10px;
    width: 100%;
  }
  .name3{
    margin-right: 65px;
    width: 100px;
  }
}

@media (min-width: 0px) and (max-width: 767px) {
  .col-sm-12 {
  	float: left;
    width: 100%;
  }
  .content-name{
    margin-right: 30px;
  }
}
@media screen and (max-width: 992px) {
  .column {
    width: 50%;
  }
}
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
    

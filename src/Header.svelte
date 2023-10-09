
<header>
        <div>
            logo
        </div>
        <div class="button-content">
            <button>Home</button>
            <button>About</button>
            <button>Login</button>
        </div>
</header>
<style>
     header {
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 10px;
}
.button-content{
    display: flex;
}
.button-content > button {
  margin-right: 10px;
  border-radius: 15px;
  width: 100px;
  border: none;
  cursor: pointer;
}

button:hover {
    opacity: 50%;
}


@media screen and (max-width: 768px) {
    .button-content {
        flex-direction: column;
        align-items: center;
  }
}
@media screen and (max-width: 768px) {
    header {
    flex-direction: column;
    align-items: flex-start;
    align-items: center;
  }
}


</style>
 
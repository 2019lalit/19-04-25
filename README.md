const obj = {
  name: "Codechef",
  arrowFunc: () => {
    console.log(this.name);
  },
  normalFunc() {
    console.log(this.name);
  }
};

obj.arrowFunc();
obj.normalFunc();

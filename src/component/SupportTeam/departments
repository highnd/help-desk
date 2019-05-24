import React, { Component } from "react";
import departments, { id, name } from "./mockdata/departments";

class departmentss extends Component {
  state = {};
  constructor(props) {
    super(props);
  }

  getdepartmentById(id) {
    return (
      <span>
        {" "}
        {
          departments.find(function(element) {
            return element.id == id;
          }).name
        }
      </span>
    );
  }
  render() {
    return this.getdepartmentById(this.props.id);
  }
}

export default departmentss;

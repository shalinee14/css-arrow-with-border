# css-arrow-with-border


 ${id} .testimonial-content:after, ${id} .testimonial-content:before {
          border: solid transparent;
          content: " ";
          display: block;
          height: 0;
          position: absolute;
          pointer-events: none;
          width: 0;
          top: 95%;
      }

        ${id} .testimonial-content:before {
          border-color: rgba(255, 255, 255, 0);
          border-bottom-color: #3d3d3d;
          left: 10%;
          margin-left: -15px;
          border-width: 17px;
          transform: rotate(-46deg);
      }
        ${id} .testimonial-content:after {
          border-color: rgba(255, 255, 255, 0);
          border-top-color: #21ebb0;
          left: 10%;
          margin-left: -11px;
          border-width: 15px;
          transform: rotate(135deg);
      }

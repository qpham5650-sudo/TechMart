using System;
using System.ComponentModel;
using System.IO;
using System.Linq;
using System.Windows.Forms;

namespace TechMart
{
    public partial class Form1 : Form
    {
        BindingList<Product> products;
        BindingSource source;
        ErrorProvider errorProvider;

        public Form1()
        {
            InitializeComponent();

            products = new BindingList<Product>();
            source = new BindingSource();

            errorProvider = new ErrorProvider();

            InitializeCategory();
            InitializeGrid();
            BindData();
        }
